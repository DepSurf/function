# Function: <code>si_domain_init</code>

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
In drivers/iommu/intel-iommu.c (ffffffff81fab68d)
Location: drivers/iommu/intel-iommu.c:2604
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff81fd826e)
Location: drivers/iommu/intel-iommu.c:2648
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff82015fb4)
Location: drivers/iommu/intel-iommu.c:2725
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff820f7c79)
Location: drivers/iommu/intel-iommu.c:2733
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff82701360)
Location: drivers/iommu/intel-iommu.c:2757
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff8272b089)
Location: drivers/iommu/intel-iommu.c:2813
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff828e3917)
Location: drivers/iommu/intel-iommu.c:2810
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff828fde68)
Location: drivers/iommu/intel-iommu.c:2723
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff82906ed0)
Location: drivers/iommu/intel-iommu.c:2734
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff82d1d7df)
Location: drivers/iommu/intel/iommu.c:2664
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff82d1d7df-ffffffff82d1da16: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8300b4fb)
Location: drivers/iommu/intel/iommu.c:2685
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8300b4fb-ffffffff8300b732: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff83215e92)
Location: drivers/iommu/intel/iommu.c:2725
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff83215e92-ffffffff832160c8: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff832ff72d)
Location: drivers/iommu/intel/iommu.c:2715
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff832ff72d-ffffffff832ff911: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff834b842f)
Location: drivers/iommu/intel/iommu.c:2450
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff834b842f-ffffffff834b86b1: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff83ef5150)
Location: drivers/iommu/intel/iommu.c:2385
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff83ef5150-ffffffff83ef5433: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8371ad10)
Location: drivers/iommu/intel/iommu.c:2349
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8371ad10-ffffffff8371afb7: si_domain_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int si_domain_init(int hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/iommu/intel/iommu.c (ffffffff8394e7f0)
Location: drivers/iommu/intel/iommu.c:2270
Inline: False
Direct callers:
  - drivers/iommu/intel/iommu.c:init_dmars
```
**Symbols:**

```
ffffffff8394e7f0-ffffffff8394ea97: si_domain_init (STB_LOCAL)
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
In drivers/iommu/intel-iommu.c (ffffffff828ee6ad)
Location: drivers/iommu/intel-iommu.c:2734
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff828e5b44)
Location: drivers/iommu/intel-iommu.c:2734
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff829021f3)
Location: drivers/iommu/intel-iommu.c:2734
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
In drivers/iommu/intel-iommu.c (ffffffff82907f32)
Location: drivers/iommu/intel-iommu.c:2734
Inline: True
Inline callers:
  - drivers/iommu/intel-iommu.c:init_dmars
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
