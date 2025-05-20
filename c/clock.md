# Function: <code>clock</code>

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
In lib/vsprintf.c (ffffffff813f4d30)
Location: lib/vsprintf.c:1341
Inline: False
```
**Symbols:**

```
ffffffff813f4d30-ffffffff813f4dd1: clock.isra.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
char *clock(char *buf, char *end, struct clk *clk, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8143aa80)
Location: lib/vsprintf.c:1387
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8143aa80-ffffffff8143aae2: clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
char *clock(char *buf, char *end, struct clk *clk, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff81457a60)
Location: lib/vsprintf.c:1387
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81457a60-ffffffff81457ac2: clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
char *clock(char *buf, char *end, struct clk *clk, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff818f9350)
Location: lib/vsprintf.c:1388
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff818f9350-ffffffff818f93b7: clock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
char *clock(char *buf, char *end, struct clk *clk, struct printf_spec spec, const char *fmt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/vsprintf.c (ffffffff8197ffb0)
Location: lib/vsprintf.c:1443
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8197ffb0-ffffffff81980017: clock (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff819dca90)
Location: lib/vsprintf.c:1465
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff819dca90-ffffffff819dcad3: clock.isra.5 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81a15460)
Location: lib/vsprintf.c:1649
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a15460-ffffffff81a154a3: clock.isra.9 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81a84e80)
Location: lib/vsprintf.c:1787
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a84e80-ffffffff81a84ede: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81abc0f0)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81abc0f0-ffffffff81abc14e: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff815f5c00)
Location: lib/vsprintf.c:1868
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815f5c00-ffffffff815f5cd6: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff8161a280)
Location: lib/vsprintf.c:1872
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8161a280-ffffffff8161a356: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff815fe400)
Location: lib/vsprintf.c:1934
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff815fe400-ffffffff815fe4d2: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff8166c0d0)
Location: lib/vsprintf.c:1951
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8166c0d0-ffffffff8166c1a2: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff817861c0)
Location: lib/vsprintf.c:1939
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff817861c0-ffffffff817862a6: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff82043290)
Location: lib/vsprintf.c:1940
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff82043290-ffffffff82043376: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff820c1820)
Location: lib/vsprintf.c:1940
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff820c1820-ffffffff820c1906: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff8219c1a0)
Location: lib/vsprintf.c:1942
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff8219c1a0-ffffffff8219c286: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffff800010d96660)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffff800010d96660-ffff800010d966d0: clock.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/vsprintf.c (c0e93a64)
Location: lib/vsprintf.c:1796
Inline: True
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
c0e93a64-c0e93ad4: clock.constprop.0 (STB_LOCAL)
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
In lib/vsprintf.c (c000000000edc180)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
c000000000edc180-c000000000edc1ac: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffe0008c06a2)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffe0008c06a2-ffffffe0008c0704: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81a5af40)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a5af40-ffffffff81a5af9e: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81a18020)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81a18020-ffffffff81a1807e: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81ac7330)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81ac7330-ffffffff81ac738e: clock.isra.0 (STB_LOCAL)
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
In lib/vsprintf.c (ffffffff81ad3810)
Location: lib/vsprintf.c:1796
Inline: False
Direct callers:
  - lib/vsprintf.c:pointer
```
**Symbols:**

```
ffffffff81ad3810-ffffffff81ad386e: clock.isra.0 (STB_LOCAL)
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
