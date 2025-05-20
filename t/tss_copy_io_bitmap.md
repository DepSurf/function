# Function: <code>tss_copy_io_bitmap</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/process.c (ffffffff81040432)
Location: arch/x86/kernel/process.c:339
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff81040382)
Location: arch/x86/kernel/process.c:341
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff81041d57)
Location: arch/x86/kernel/process.c:353
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff81048027)
Location: arch/x86/kernel/process.c:370
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
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
In arch/x86/kernel/process.c (ffffffff810512c7)
Location: arch/x86/kernel/process.c:386
Inline: True
Inline callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void tss_copy_io_bitmap(struct tss_struct *tss, struct io_bitmap *iobm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:386
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
**Symbols:**

```
ffffffff8105df50-ffffffff8105dffd: tss_copy_io_bitmap (STB_LOCAL)
ffffffff820525f2-ffffffff8205260d: tss_copy_io_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void tss_copy_io_bitmap(struct tss_struct *tss, struct io_bitmap *iobm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:414
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
**Symbols:**

```
ffffffff8105f600-ffffffff8105f6ad: tss_copy_io_bitmap (STB_LOCAL)
ffffffff820d0ac9-ffffffff820d0ae4: tss_copy_io_bitmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void tss_copy_io_bitmap(struct tss_struct *tss, struct io_bitmap *iobm);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/process.c (0)
Location: arch/x86/kernel/process.c:426
Inline: False
Direct callers:
  - arch/x86/kernel/process.c:native_tss_update_io_bitmap
```
**Symbols:**

```
ffffffff810666b0-ffffffff8106675d: tss_copy_io_bitmap (STB_LOCAL)
ffffffff821ab5f2-ffffffff821ab60d: tss_copy_io_bitmap.cold (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
