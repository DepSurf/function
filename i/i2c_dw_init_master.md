# Function: <code>i2c_dw_init_master</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81726840)
Location: drivers/i2c/busses/i2c-designware-master.c:54
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81726840-ffffffff81726c1a: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81797e90)
Location: drivers/i2c/busses/i2c-designware-master.c:54
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81797e90-ffffffff8179826a: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff817dab30)
Location: drivers/i2c/busses/i2c-designware-master.c:56
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_probe
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff817dab30-ffffffff817daf1f: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81802440)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81802440-ffffffff81802551: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818432e0)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818432e0-ffffffff81843408: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81874c60)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81874c60-ffffffff81874d88: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81949f19)
Location: drivers/i2c/busses/i2c-designware-master.c:182
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81949b40-ffffffff81949b65: i2c_dw_init_master (STB_LOCAL)
ffffffff81949a10-ffffffff81949b34: i2c_dw_init_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8194fbd9)
Location: drivers/i2c/busses/i2c-designware-master.c:182
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff8194f700-ffffffff8194f725: i2c_dw_init_master (STB_LOCAL)
ffffffff8194f5d0-ffffffff8194f6f4: i2c_dw_init_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81933a99)
Location: drivers/i2c/busses/i2c-designware-master.c:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81932fb0-ffffffff819330d4: i2c_dw_init_master.part.0 (STB_LOCAL)
ffffffff819330e0-ffffffff81933105: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff819d6e69)
Location: drivers/i2c/busses/i2c-designware-master.c:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff819d6360-ffffffff819d6484: i2c_dw_init_master.part.0 (STB_LOCAL)
ffffffff819d6490-ffffffff819d64b5: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81b399c7)
Location: drivers/i2c/busses/i2c-designware-master.c:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81b38eb0-ffffffff81b38fbf: i2c_dw_init_master.part.0 (STB_LOCAL)
ffffffff81b38fc0-ffffffff81b38fea: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ccf107)
Location: drivers/i2c/busses/i2c-designware-master.c:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81cce820-ffffffff81cce92f: i2c_dw_init_master.part.0 (STB_LOCAL)
ffffffff81cce940-ffffffff81cce96a: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81d36df7)
Location: drivers/i2c/busses/i2c-designware-master.c:175
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81d365f0-ffffffff81d366ff: i2c_dw_init_master.part.0 (STB_LOCAL)
ffffffff81d36710-ffffffff81d3673f: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff81ded007)
Location: drivers/i2c/busses/i2c-designware-master.c:176
Inline: True
Inline callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff81dec3b0-ffffffff81dec4bf: i2c_dw_init_master.part.0 (STB_LOCAL)
ffffffff81dec4d0-ffffffff81dec4ff: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffff800010ab9a00)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffff800010ab9a00-ffff800010ab9b14: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c0b99098)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c0b99098-c0b991bc: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (c000000000b9d430)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
c000000000b9d430-c000000000b9d5c4: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffe0006bec02)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffe0006bec02-ffffffe0006bed14: i2c_dw_init_master (STB_LOCAL)
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
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff8186a110)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff8186a110-ffffffff8186a238: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int i2c_dw_init_master(struct dw_i2c_dev *dev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/i2c/busses/i2c-designware-master.c (ffffffff818840a0)
Location: drivers/i2c/busses/i2c-designware-master.c:153
Inline: True
Direct callers:
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_unprepare_recovery
  - drivers/i2c/busses/i2c-designware-master.c:i2c_dw_xfer
```
**Symbols:**

```
ffffffff818840a0-ffffffff818841c8: i2c_dw_init_master (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
