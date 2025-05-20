# Function: <code>ddebug_change</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814148f7)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8145c469)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8147af59)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81484242)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814c0282)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff814f12f9)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8150503c)
Location: lib/dynamic_debug.c:138
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81533070)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81553eb0)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ddebug_change(const struct ddebug_query *query, unsigned int flags, unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:140
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff815dcd80-ffffffff815dd03c: ddebug_change (STB_LOCAL)
ffffffff815ddeac-ffffffff815ddf0f: ddebug_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:148
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff815fa4d0-ffffffff815fa786: ddebug_change (STB_LOCAL)
ffffffff81bf40ba-ffffffff81bf4112: ddebug_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:148
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff815dd0b0-ffffffff815dd362: ddebug_change (STB_LOCAL)
ffffffff81be5f39-ffffffff81be5f91: ddebug_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:148
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff81648a10-ffffffff81648d18: ddebug_change (STB_LOCAL)
ffffffff81cdd778-ffffffff81cdd7d1: ddebug_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/dynamic_debug.c (0)
Location: lib/dynamic_debug.c:152
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff8175ee90-ffffffff8175f1cc: ddebug_change (STB_LOCAL)
ffffffff81ea3aeb-ffffffff81ea3b37: ddebug_change.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8188de20)
Location: lib/dynamic_debug.c:173
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff8188de20-ffffffff8188e313: ddebug_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff818d0390)
Location: lib/dynamic_debug.c:173
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff818d0390-ffffffff818d0883: ddebug_change (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ddebug_change(const struct ddebug_query *query, struct flag_settings *modifiers);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81922370)
Location: lib/dynamic_debug.c:174
Inline: False
Direct callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
**Symbols:**

```
ffffffff81922370-ffffffff81922854: ddebug_change (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffff800010660384)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c0809550)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_queries
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (c0000000008139c8)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffe00048d0fc)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8154c490)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff8153c770)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff815481d0)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/dynamic_debug.c (ffffffff81562020)
Location: lib/dynamic_debug.c:140
Inline: True
Inline callers:
  - lib/dynamic_debug.c:ddebug_exec_query
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct flag_settings *modifiers</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int mask</code>
</li>
</ul>
</details>
</li>
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
