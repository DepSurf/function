# Function: <code>find_link</code>

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
In init/initramfs.c (ffffffff81f5c575)
Location: init/initramfs.c:70
Inline: True
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
In init/initramfs.c (ffffffff81f8452f)
Location: init/initramfs.c:70
Inline: True
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
In init/initramfs.c (ffffffff81fbfab1)
Location: init/initramfs.c:70
Inline: True
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
In init/initramfs.c (ffffffff8209f7f0)
Location: init/initramfs.c:71
Inline: True
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
In init/initramfs.c (ffffffff826a57f0)
Location: init/initramfs.c:72
Inline: True
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
In init/initramfs.c (ffffffff826cec15)
Location: init/initramfs.c:72
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff82884c5a)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff8289bc9c)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff8289ec81)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82cc4c01)
Location: init/initramfs.c:63
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff82cc4c01-ffffffff82cc4cec: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82fb0558)
Location: init/initramfs.c:66
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff82fb0558-ffffffff82fb0643: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff831ba5c9)
Location: init/initramfs.c:78
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff831ba5c9-ffffffff831ba6b4: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8329aaa1)
Location: init/initramfs.c:79
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff8329aaa1-ffffffff8329ab8c: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8344921d)
Location: init/initramfs.c:90
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff8344921d-ffffffff83449342: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83e62c20)
Location: init/initramfs.c:90
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff83e62c20-ffffffff83e62d5c: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff83683230)
Location: init/initramfs.c:84
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff83683230-ffffffff8368337a: find_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff838b2210)
Location: init/initramfs.c:84
Inline: False
Direct callers:
  - init/initramfs.c:maybe_link
```
**Symbols:**

```
ffffffff838b2210-ffffffff838b2389: find_link (STB_LOCAL)
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
In init/initramfs.c (ffff800011432f34)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (c1503038)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
char *find_link(int major, int minor, int ino, umode_t mode, char *name);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In init/initramfs.c (c000000001346a90)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
```
```
In arch/powerpc/platforms/powernv/ocxl.c (c0000000000e6370)
Location: arch/powerpc/platforms/powernv/ocxl.c:138
Inline: False
Direct callers:
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_get_pasid_count
  - arch/powerpc/platforms/powernv/ocxl.c:pnv_ocxl_fixup_actag
```
**Symbols:**

```
c0000000000e6370-c0000000000e64a8: find_link (STB_LOCAL)
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
In init/initramfs.c (ffffffe000002998)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff8288cc81)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff8288abfe)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff8289fc81)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
In init/initramfs.c (ffffffff8289fc86)
Location: init/initramfs.c:62
Inline: True
Inline callers:
  - init/initramfs.c:maybe_link
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
<b>Arch</b>
<ul>
</ul>
