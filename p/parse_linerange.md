# Function: <code>parse_linerange</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:306
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff815fae70-ffffffff815faf3c: parse_linerange (STB_LOCAL)
ffffffff81bf4245-ffffffff81bf42bc: parse_linerange.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:306
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff815ddaf0-ffffffff815ddbbc: parse_linerange (STB_LOCAL)
ffffffff81be6117-ffffffff81be618e: parse_linerange.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:306
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff81648f50-ffffffff8164901c: parse_linerange (STB_LOCAL)
ffffffff81cdd840-ffffffff81cdd8b7: parse_linerange.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:310
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff8175fbe0-ffffffff8175fcea: parse_linerange (STB_LOCAL)
ffffffff81ea3d89-ffffffff81ea3de6: parse_linerange.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188d8a0)
Location: lib/dynamic_debug.c:348
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff8188d8a0-ffffffff8188d9fd: parse_linerange (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818cfe10)
Location: lib/dynamic_debug.c:348
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff818cfe10-ffffffff818cff71: parse_linerange (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_linerange(struct ddebug_query *query, const char *first);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81921df0)
Location: lib/dynamic_debug.c:349
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_parse_query
  - lib/dynamic_debug.c:ddebug_parse_query
```
**Symbols:**

```
ffffffff81921df0-ffffffff81921f51: parse_linerange (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
