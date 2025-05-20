# Function: <code>i2c_init_recovery</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core.c (ffffffff816ddc24)
Location: drivers/i2c/i2c-core.c:765
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
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
In drivers/i2c/i2c-core.c (ffffffff8170df99)
Location: drivers/i2c/i2c-core.c:862
Inline: True
Inline callers:
  - drivers/i2c/i2c-core.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff81721237)
Location: drivers/i2c/i2c-core-base.c:262
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff817925bd)
Location: drivers/i2c/i2c-core-base.c:267
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff817d4fd0)
Location: drivers/i2c/i2c-core-base.c:246
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff817fc120)
Location: drivers/i2c/i2c-core-base.c:255
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff8183d092)
Location: drivers/i2c/i2c-core-base.c:247
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff8186ea91)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81942ab1)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81948dfd)
Location: drivers/i2c/i2c-core-base.c:378
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int i2c_init_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:400
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff8192a1b0-ffffffff8192a39e: i2c_init_recovery (STB_LOCAL)
ffffffff81c16827-ffffffff81c1689a: i2c_init_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int i2c_init_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:400
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff819cd320-ffffffff819cd53a: i2c_init_recovery (STB_LOCAL)
ffffffff81d25512-ffffffff81d25557: i2c_init_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int i2c_init_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/i2c/i2c-core-base.c (0)
Location: drivers/i2c/i2c-core-base.c:400
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81b2f420-ffffffff81b2f64e: i2c_init_recovery (STB_LOCAL)
ffffffff81ef13cd-ffffffff81ef1411: i2c_init_recovery.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int i2c_init_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81cc32e0)
Location: drivers/i2c/i2c-core-base.c:400
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81cc32e0-ffffffff81cc3552: i2c_init_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int i2c_init_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81d2ae30)
Location: drivers/i2c/i2c-core-base.c:422
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81d2ae30-ffffffff81d2b0a2: i2c_init_recovery (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int i2c_init_recovery(struct i2c_adapter *adap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/i2c/i2c-core-base.c (ffffffff81de0cf0)
Location: drivers/i2c/i2c-core-base.c:425
Inline: False
Direct callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
**Symbols:**

```
ffffffff81de0cf0-ffffffff81de0f62: i2c_init_recovery (STB_LOCAL)
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
In drivers/i2c/i2c-core-base.c (ffff800010ab227c)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (c0b93900)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (c000000000b959d4)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffe0006b9f68)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff81862c21)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
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
In drivers/i2c/i2c-core-base.c (ffffffff8187de81)
Location: drivers/i2c/i2c-core-base.c:254
Inline: True
Inline callers:
  - drivers/i2c/i2c-core-base.c:i2c_register_adapter
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
