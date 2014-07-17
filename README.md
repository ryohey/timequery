# timequery

### Time String

- "century"
- "year"
- "week"
- "day"
- "hour"
- "minute"
- "second"

### Constructor

### $t(time, date)

```
$t(new Date, "year")
```

### Filter

#### every(time)

```
every("day").every("second")
```

#### nth(count)

```
nth(10, "century");
```

#### first(time)

```
every("month").first("day")
```

every period -> [[day], [day]]
every year -> [[day], [day]]
every week -> [[day], [day]]
every day -> [day]
