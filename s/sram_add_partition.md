# Function: <code>sram_add_partition</code>

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
In drivers/misc/sram.c (ffffffff81579ab8)
Location: drivers/misc/sram.c:127
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff815cebad)
Location: drivers/misc/sram.c:127
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff815fb80d)
Location: drivers/misc/sram.c:132
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff8160f5b3)
Location: drivers/misc/sram.c:106
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff81677e33)
Location: drivers/misc/sram.c:106
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff816b387e)
Location: drivers/misc/sram.c:106
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff816d4b3e)
Location: drivers/misc/sram.c:106
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_probe
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
In drivers/misc/sram.c (ffffffff8171029f)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (ffffffff8173458f)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff817f19d0-ffffffff817f1b26: sram_add_partition (STB_LOCAL)
ffffffff817f1e64-ffffffff817f1e80: sram_add_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81806000-ffffffff81806156: sram_add_partition (STB_LOCAL)
ffffffff81c0fe12-ffffffff81c0fe2e: sram_add_partition.cold (STB_LOCAL)
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
In drivers/misc/sram.c (ffffffff817eae03)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff818774e0-ffffffff818776d1: sram_add_partition (STB_LOCAL)
ffffffff81d05d25-ffffffff81d05dc9: sram_add_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff819bf7a0-ffffffff819bf993: sram_add_partition (STB_LOCAL)
ffffffff81ece639-ffffffff81ece6e6: sram_add_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81b34fb0-ffffffff81b351d5: sram_add_partition (STB_LOCAL)
ffffffff82099c99-ffffffff82099d07: sram_add_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81b88480-ffffffff81b8869c: sram_add_partition (STB_LOCAL)
ffffffff8211adb4-ffffffff8211ae1c: sram_add_partition.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sram_add_partition(struct sram_dev *sram, struct sram_reserve *block, phys_addr_t start);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/misc/sram.c (0)
Location: drivers/misc/sram.c:93
Inline: False
Direct callers:
  - drivers/misc/sram.c:sram_reserve_regions
```
**Symbols:**

```
ffffffff81bdc340-ffffffff81bdc56a: sram_add_partition (STB_LOCAL)
ffffffff821f8c3a-ffffffff821f8ca3: sram_add_partition.cold (STB_LOCAL)
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
In drivers/misc/sram.c (ffff80001092b538)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (c0a09d1c)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (c0000000009ca648)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (ffffffe0005a2d14)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (ffffffff816fa61f)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (ffffffff816ce42f)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (ffffffff81727a4f)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
In drivers/misc/sram.c (ffffffff81742e8f)
Location: drivers/misc/sram.c:93
Inline: True
Inline callers:
  - drivers/misc/sram.c:sram_reserve_regions
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
