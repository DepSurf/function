# Function: <code>common_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int common_mmap(const char *op, struct file *file, long unsigned int prot, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81384d40)
Location: security/apparmor/lsm.c:500
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
```
**Symbols:**

```
ffffffff81384d40-ffffffff81384d90: common_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int common_mmap(const char *op, struct file *file, long unsigned int prot, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813bf320)
Location: security/apparmor/lsm.c:473
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
```
**Symbols:**

```
ffffffff813bf320-ffffffff813bf36d: common_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int common_mmap(const char *op, struct file *file, long unsigned int prot, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813d7530)
Location: security/apparmor/lsm.c:476
Inline: False
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
```
**Symbols:**

```
ffffffff813d7530-ffffffff813d757d: common_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff813e83c5)
Location: security/apparmor/lsm.c:459
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff813e8370-ffffffff813e83ab: common_mmap.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8140f7e5)
Location: security/apparmor/lsm.c:459
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff8140f790-ffffffff8140f7cb: common_mmap.part.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff81441d5e)
Location: security/apparmor/lsm.c:488
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff81441d10-ffffffff81441d4b: common_mmap.part.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8145e74e)
Location: security/apparmor/lsm.c:483
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff8145e700-ffffffff8145e73b: common_mmap.part.13 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148bc4e)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff8148bc00-ffffffff8148bc38: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814a5b0e)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff814a5ac0-ffffffff814a5af8: common_mmap.part.0 (STB_LOCAL)
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
In security/apparmor/lsm.c (ffffffff8150271f)
Location: security/apparmor/lsm.c:494
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff8151f0d7)
Location: security/apparmor/lsm.c:494
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff815258bb)
Location: security/apparmor/lsm.c:503
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff81583b4b)
Location: security/apparmor/lsm.c:503
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff8162481d)
Location: security/apparmor/lsm.c:696
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff816d7789)
Location: security/apparmor/lsm.c:738
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff8171255d)
Location: security/apparmor/lsm.c:736
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
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
In security/apparmor/lsm.c (ffffffff8175022d)
Location: security/apparmor/lsm.c:734
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_file_mprotect
  - security/apparmor/lsm.c:apparmor_mmap_file
  - security/apparmor/lsm.c:apparmor_mmap_file
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffff80001059bf20)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffff80001059be88-ffff80001059beec: common_mmap.part.0 (STB_LOCAL)
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
In security/apparmor/lsm.c (c074d4e4)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
c074d478-c074d4bc: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (c000000000713ebc)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
c000000000713e40-c000000000713e8c: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffe0003e7bd6)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffe0003e7b50-ffffffe0003e7bb0: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149e0ee)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff8149e0a0-ffffffff8149e0d8: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8148eb0e)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff8148eac0-ffffffff8148eaf8: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff8149a18e)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff8149a140-ffffffff8149a178: common_mmap.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/lsm.c (ffffffff814b22be)
Location: security/apparmor/lsm.c:479
Inline: True
Inline callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
Direct callers:
  - security/apparmor/lsm.c:apparmor_file_mprotect
```
**Symbols:**

```
ffffffff814b2270-ffffffff814b22a8: common_mmap.part.0 (STB_LOCAL)
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
</ul>
