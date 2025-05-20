# Function: <code>calc_checksum</code>

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
In mm/ksm.c (ffffffff811e59be)
Location: mm/ksm.c:829
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
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
In mm/ksm.c (ffffffff81204726)
Location: mm/ksm.c:817
Inline: True
Inline callers:
  - mm/ksm.c:ksm_scan_thread
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81215150)
Location: mm/ksm.c:828
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81215150-ffffffff8121528d: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81220510)
Location: mm/ksm.c:985
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81220510-ffffffff81220610: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8123b750)
Location: mm/ksm.c:985
Inline: False
Direct callers:
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8123b750-ffffffff8123b850: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8125ece0)
Location: mm/ksm.c:1008
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff8125ece0-ffffffff8125ede3: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81273510)
Location: mm/ksm.c:1009
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_scan_thread
```
**Symbols:**

```
ffffffff81273510-ffffffff81273556: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8128ed10)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8128ed10-ffffffff8128ed56: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8129ea80)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8129ea80-ffffffff8129eac6: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812d3110)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812d3110-ffffffff812d3159: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812deac0)
Location: mm/ksm.c:1024
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812deac0-ffffffff812deb09: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812e62a0)
Location: mm/ksm.c:1022
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812e62a0-ffffffff812e62e9: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8132e540)
Location: mm/ksm.c:1018
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8132e540-ffffffff8132e589: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8139e430)
Location: mm/ksm.c:1031
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8139e430-ffffffff8139e4a8: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff8141db50)
Location: mm/ksm.c:1035
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff8141db50-ffffffff8141dbc8: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff814525b0)
Location: mm/ksm.c:1079
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff814525b0-ffffffff81452628: calc_checksum (STB_LOCAL)
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
In mm/ksm.c (ffffffff8391dd08)
Location: mm/ksm.c:1269
Inline: True
Inline callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffff80001033e298)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffff80001033e298-ffff80001033e2fc: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c0544700)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_do_scan
```
**Symbols:**

```
c0544700-c054473c: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (c000000000419c50)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
c000000000419c50-c000000000419cd0: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffe0002335f2)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:ksm_do_scan
```
**Symbols:**

```
ffffffe0002335f2-ffffffe000233656: calc_checksum (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81297060)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81297060-ffffffff812970a6: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81288c70)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81288c70-ffffffff81288cb6: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff81294e70)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff81294e70-ffffffff81294eb6: calc_checksum (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 calc_checksum(struct page *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/ksm.c (ffffffff812a4ce0)
Location: mm/ksm.c:1023
Inline: False
Direct callers:
  - mm/ksm.c:ksm_init
  - mm/ksm.c:cmp_and_merge_page
```
**Symbols:**

```
ffffffff812a4ce0-ffffffff812a4d3e: calc_checksum (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
