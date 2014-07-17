# timequery

### Time String

- "century"
- "year"
- "month"
- "week"
- "day"
- "hour"
- "minute"
- "second"

### Constructor

### $t(timeString)

```
$t("year")
```

### Filter

#### every(time)

```
$t("day").every($t("second"))
```

#### eq(count)

```
$t("century").eq(10);
```

#### first(time)

```
$t("month").first($t("day"));
```

#### odd(), even()

#### has(time)

```
$t("month").has($t("day").eq(31));
```

