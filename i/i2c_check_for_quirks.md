# Function: <code>i2c_check_for_quirks</code>

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
In drivers/i2c/i2c-core.c (ffffffff81679900)
Location: drivers/i2c/i2c-core.c:2110
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:__i2c_transfer
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
In drivers/i2c/i2c-core.c (ffffffff816db0c0)
Location: drivers/i2c/i2c-core.c:2315
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:__i2c_transfer
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
In drivers/i2c/i2c-core.c (ffffffff8170b400)
Location: drivers/i2c/i2c-core.c:2601
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:__i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff8172044f)
Location: drivers/i2c/i2c-core-base.c:1787
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff8179177f)
Location: drivers/i2c/i2c-core-base.c:1811
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff817d41a0)
Location: drivers/i2c/i2c-core-base.c:1790
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff817fb2e2)
Location: drivers/i2c/i2c-core-base.c:1795
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:__i2c_transfer
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
In drivers/i2c/i2c-core-base.c (ffffffff8183bfef)
Location: drivers/i2c/i2c-core-base.c:1885
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff8186dc38)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1820
Inline: False
```
**Symbols:**

```
ffffffff819419a0-ffffffff81941c2d: i2c_check_for_quirks (STB_LOCAL)
ffffffff81943249-ffffffff819433b3: i2c_check_for_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:1950
Inline: False
```
**Symbols:**

```
ffffffff81947d50-ffffffff81947fdd: i2c_check_for_quirks (STB_LOCAL)
ffffffff81c248d6-ffffffff81c24a40: i2c_check_for_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2010
Inline: False
```
**Symbols:**

```
ffffffff8192b6b0-ffffffff8192b93d: i2c_check_for_quirks (STB_LOCAL)
ffffffff81c169e6-ffffffff81c16b50: i2c_check_for_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2011
Inline: False
```
**Symbols:**

```
ffffffff819ce890-ffffffff819ceb1d: i2c_check_for_quirks (STB_LOCAL)
ffffffff81d256cb-ffffffff81d25835: i2c_check_for_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:2014
Inline: False
```
**Symbols:**

```
ffffffff81b30580-ffffffff81b3080c: i2c_check_for_quirks (STB_LOCAL)
ffffffff81ef14a3-ffffffff81ef15db: i2c_check_for_quirks.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc4d80)
Location: drivers/i2c/i2c-core-base.c:2008
Inline: False
```
**Symbols:**

```
ffffffff81cc4d80-ffffffff81cc5121: i2c_check_for_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2ca20)
Location: drivers/i2c/i2c-core-base.c:2121
Inline: False
```
**Symbols:**

```
ffffffff81d2ca20-ffffffff81d2cdc1: i2c_check_for_quirks (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_check_for_quirks(struct i2c_adapter *adap, struct i2c_msg *msgs, int num);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de28f0)
Location: drivers/i2c/i2c-core-base.c:2139
Inline: False
```
**Symbols:**

```
ffffffff81de28f0-ffffffff81de2c91: i2c_check_for_quirks (STB_LOCAL)
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
In drivers/i2c/i2c-core-base.c (ffff800010ab1538)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
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
In drivers/i2c/i2c-core-base.c (c0b9259c)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
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
In drivers/i2c/i2c-core-base.c (c000000000b93fc4)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b904c)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
```
</details>
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
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81861dc8)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
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
In drivers/i2c/i2c-core-base.c (ffffffff8187d028)
Location: drivers/i2c/i2c-core-base.c:1890
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
