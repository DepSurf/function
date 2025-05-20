# Function: <code>pci_mmconfig_alloc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff816f7010)
Location: arch/x86/pci/mmconfig-shared.c:67
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
```
**Symbols:**

```
ffffffff816f7010-ffffffff816f70dd: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8175bca0)
Location: arch/x86/pci/mmconfig-shared.c:67
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff8175bca0-ffffffff8175bd6d: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81788210)
Location: arch/x86/pci/mmconfig-shared.c:67
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81788210-ffffffff817882dd: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff817a7310)
Location: arch/x86/pci/mmconfig-shared.c:67
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff817a7310-ffffffff817a73d3: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8181e570)
Location: arch/x86/pci/mmconfig-shared.c:68
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff8181e570-ffffffff8181e633: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818687d0)
Location: arch/x86/pci/mmconfig-shared.c:68
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff818687d0-ffffffff81868885: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81888720)
Location: arch/x86/pci/mmconfig-shared.c:68
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81888720-ffffffff818887d5: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818d3050)
Location: arch/x86/pci/mmconfig-shared.c:68
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff818d3050-ffffffff818d310b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff819053d0)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff819053d0-ffffffff8190548b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bb5ac0)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81bb5ac0-ffffffff81bb5b7b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bcac70)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81bcac70-ffffffff81bcad2b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81bbe5b0)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81bbe5b0-ffffffff81bbe66b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81c8e4f0)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81c8e4f0-ffffffff81c8e5ab: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81e3d570)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81e3d570-ffffffff81e3d63d: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff820169a0)
Location: arch/x86/pci/mmconfig-shared.c:70
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff820169a0-ffffffff82016a6d: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff82096d50)
Location: arch/x86/pci/mmconfig-shared.c:70
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff82096d50-ffffffff82096e17: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8216e1c0)
Location: arch/x86/pci/mmconfig-shared.c:70
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff8216e1c0-ffffffff8216e2b6: pci_mmconfig_alloc (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818a4790)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff818a4790-ffffffff818a484b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff8185ff50)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff8185ff50-ffffffff8186000b: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff818f5df0)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff818f5df0-ffffffff818f5eab: pci_mmconfig_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct pci_mmcfg_region *pci_mmconfig_alloc(int segment, int start, int end, u64 addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/pci/mmconfig-shared.c (ffffffff81916ee0)
Location: arch/x86/pci/mmconfig-shared.c:69
Inline: False
Direct callers:
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_insert
  - arch/x86/pci/mmconfig-shared.c:pci_mmconfig_add
```
**Symbols:**

```
ffffffff81916ee0-ffffffff81916f9b: pci_mmconfig_alloc (STB_LOCAL)
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
