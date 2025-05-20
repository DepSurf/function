# Function: <code>resource_string</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff813f43b0)
Location: lib/vsprintf.c:648
Inline: False
```
**Symbols:**

```
ffffffff813f43b0-ffffffff813f47af: resource_string.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *resource_string(char *buf, char *end, struct resource *res, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143a030)
Location: lib/vsprintf.c:695
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8143a030-ffffffff8143a376: resource_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *resource_string(char *buf, char *end, struct resource *res, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81457010)
Location: lib/vsprintf.c:695
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81457010-ffffffff81457356: resource_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *resource_string(char *buf, char *end, struct resource *res, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f88d0)
Location: lib/vsprintf.c:696
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f88d0-ffffffff818f8c1a: resource_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *resource_string(char *buf, char *end, struct resource *res, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197f3a0)
Location: lib/vsprintf.c:698
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197f3a0-ffffffff8197f6ea: resource_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff819dcae0)
Location: lib/vsprintf.c:723
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819dcae0-ffffffff819dce40: resource_string.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a14f40)
Location: lib/vsprintf.c:841
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a14f40-ffffffff81a152a0: resource_string.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a849f0)
Location: lib/vsprintf.c:954
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a849f0-ffffffff81a84d58: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81abbc60)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81abbc60-ffffffff81abbfc8: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff815f7b50)
Location: lib/vsprintf.c:1010
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815f7b50-ffffffff815f8273: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff8161c210)
Location: lib/vsprintf.c:1013
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8161c210-ffffffff8161c933: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff815ffa80)
Location: lib/vsprintf.c:1039
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815ffa80-ffffffff816001a3: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff8166d9a0)
Location: lib/vsprintf.c:1044
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8166d9a0-ffffffff8166e0c3: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81787d40)
Location: lib/vsprintf.c:1040
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81787d40-ffffffff81788382: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff82045010)
Location: lib/vsprintf.c:1041
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff82045010-ffffffff82045652: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff820c3650)
Location: lib/vsprintf.c:1041
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff820c3650-ffffffff820c3c8f: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff8219dfd0)
Location: lib/vsprintf.c:1043
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8219dfd0-ffffffff8219e60f: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffff800010d961f8)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffff800010d961f8-ffff800010d964f8: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
char *resource_string(char *buf, char *end, struct resource *res, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (c0e91e40)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
c0e91e40-c0e92224: resource_string (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (c000000000edc320)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
c000000000edc320-c000000000edc704: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffe0008c0266)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffe0008c0266-ffffffe0008c0588: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a5aab0)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a5aab0-ffffffff81a5ae18: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81a17b90)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a17b90-ffffffff81a17ef8: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81ac6ea0)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81ac6ea0-ffffffff81ac7208: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (ffffffff81ad3380)
Location: lib/vsprintf.c:963
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81ad3380-ffffffff81ad36e8: resource_string.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
