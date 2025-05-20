# Function: <code>clear_dte_entry</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8152e6a0)
Location: drivers/iommu/amd_iommu.c:1877
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff8152e6a0-ffffffff8152e6de: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81581b90)
Location: drivers/iommu/amd_iommu.c:1757
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff81581b90-ffffffff81581bce: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815ae500)
Location: drivers/iommu/amd_iommu.c:1850
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff815ae500-ffffffff815ae53e: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff815c3e80)
Location: drivers/iommu/amd_iommu.c:2097
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff815c3e80-ffffffff815c3ebe: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff8162abd0)
Location: drivers/iommu/amd_iommu.c:1868
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff8162abd0-ffffffff8162ac0e: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81665800)
Location: drivers/iommu/amd_iommu.c:1879
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:__detach_device
  - drivers/iommu/amd_iommu.c:__detach_device
```
**Symbols:**

```
ffffffff81665800-ffffffff8166583e: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff81684270)
Location: drivers/iommu/amd_iommu.c:1960
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff81684270-ffffffff816842ae: clear_dte_entry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void clear_dte_entry(u16 devid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816bb7e0)
Location: drivers/iommu/amd_iommu.c:1959
Inline: False
Direct callers:
  - drivers/iommu/amd_iommu.c:do_detach
  - drivers/iommu/amd_iommu.c:do_detach
```
**Symbols:**

```
ffffffff816bb7e0-ffffffff816bb81e: clear_dte_entry (STB_LOCAL)
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
In drivers/iommu/amd_iommu.c (ffffffff816e145f)
Location: drivers/iommu/amd_iommu.c:2023
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd/iommu.c (ffffffff81796b51)
Location: drivers/iommu/amd/iommu.c:1881
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
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
In drivers/iommu/amd/iommu.c (ffffffff817a5271)
Location: drivers/iommu/amd/iommu.c:1972
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81789921)
Location: drivers/iommu/amd/iommu.c:1464
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81810b51)
Location: drivers/iommu/amd/iommu.c:1513
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81951241)
Location: drivers/iommu/amd/iommu.c:1535
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81ab63ca)
Location: drivers/iommu/amd/iommu.c:1625
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b0256f)
Location: drivers/iommu/amd/iommu.c:1650
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd/iommu.c (ffffffff81b568df)
Location: drivers/iommu/amd/iommu.c:1792
Inline: True
Inline callers:
  - drivers/iommu/amd/iommu.c:do_detach
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/iommu/amd_iommu.c (ffffffff816a6eaf)
Location: drivers/iommu/amd_iommu.c:2023
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff8168489f)
Location: drivers/iommu/amd_iommu.c:2023
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff816d511f)
Location: drivers/iommu/amd_iommu.c:2023
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:do_detach
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
In drivers/iommu/amd_iommu.c (ffffffff816ef81f)
Location: drivers/iommu/amd_iommu.c:2023
Inline: True
Inline callers:
  - drivers/iommu/amd_iommu.c:do_detach
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
</ul>
