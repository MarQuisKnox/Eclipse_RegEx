# Eclipse RegEx
RegEx for Eclipse

## Find SQL ID values
```perl
VALUES\([0-9]+,
```

## Find a comma followed by anything
```perl
\,+(.*)
```

## Find a comma followed by two quotation marks & a blank line
```perl
\,""+(\n)
```

## Find a comma followed by a line break
```perl
\,+(\n)
```

## Find SQL comments
```perl
/+(.*)/;
```

## Find Blank Lines
```perl
^\s*\n
```
