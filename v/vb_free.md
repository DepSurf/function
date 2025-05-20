# Function: <code>vb_free</code>

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
In mm/vmalloc.c (ffffffff811ce5cc)
Location: mm/vmalloc.c:987
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff811eb20c)
Location: mm/vmalloc.c:1011
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff811fc472)
Location: mm/vmalloc.c:982
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff81207142)
Location: mm/vmalloc.c:1033
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff81220232)
Location: mm/vmalloc.c:1031
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff81241b1f)
Location: mm/vmalloc.c:1014
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff8125621f)
Location: mm/vmalloc.c:1014
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff81269205)
Location: mm/vmalloc.c:1617
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff81278135)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812ab800)
Location: mm/vmalloc.c:1726
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812ab800-ffffffff812ab8fc: vb_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812b6d20)
Location: mm/vmalloc.c:1715
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812b6d20-ffffffff812b6e19: vb_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmalloc.c (ffffffff812bc5e0)
Location: mm/vmalloc.c:1985
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812bc5e0-ffffffff812bc6da: vb_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2037
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff812fed50-ffffffff812fee64: vb_free (STB_LOCAL)
ffffffff81cbcfe1-ffffffff81cbd02e: vb_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2055
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81365b80-ffffffff81365ca9: vb_free (STB_LOCAL)
ffffffff81e6ecbf-ffffffff81e6ed0b: vb_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2117
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff813e16a0-ffffffff813e17c9: vb_free (STB_LOCAL)
ffffffff82064ba4-ffffffff82064bf0: vb_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2217
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81416410-ffffffff814165ab: vb_free (STB_LOCAL)
ffffffff820e42e8-ffffffff820e4390: vb_free.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void vb_free(long unsigned int addr, long unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/vmalloc.c (0)
Location: mm/vmalloc.c:2217
Inline: False
Direct callers:
  - mm/vmalloc.c:vm_unmap_ram
```
**Symbols:**

```
ffffffff81442ee0-ffffffff8144307b: vb_free (STB_LOCAL)
ffffffff821c0f1c-ffffffff821c0fc4: vb_free.cold (STB_LOCAL)
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
In mm/vmalloc.c (ffff80001030e808)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (c052a20c)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (c0000000003df6c0)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffe0002171da)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff81270785)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff812626f5)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff8126e525)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
In mm/vmalloc.c (ffffffff8127defb)
Location: mm/vmalloc.c:1625
Inline: True
Inline callers:
  - mm/vmalloc.c:vm_unmap_ram
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
