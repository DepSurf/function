# Function: <code>kexec_free_initrd</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff8289c2fd)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (ffffffff8289f2ed)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool kexec_free_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82cc57a1)
Location: init/initramfs.c:545
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
```
**Symbols:**

```
ffffffff82cc57a1-ffffffff82cc581c: kexec_free_initrd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool kexec_free_initrd();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/initramfs.c (ffffffff82fb10a9)
Location: init/initramfs.c:552
Inline: False
Direct callers:
  - init/initramfs.c:populate_rootfs
```
**Symbols:**

```
ffffffff82fb10a9-ffffffff82fb1124: kexec_free_initrd (STB_LOCAL)
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
In init/initramfs.c (ffffffff831bb2e6)
Location: init/initramfs.c:617
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
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
In init/initramfs.c (ffffffff8329b7ee)
Location: init/initramfs.c:618
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
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
In init/initramfs.c (ffffffff83449d54)
Location: init/initramfs.c:643
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
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
In init/initramfs.c (ffffffff83e6429f)
Location: init/initramfs.c:643
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
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
In init/initramfs.c (ffffffff836848db)
Location: init/initramfs.c:636
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
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
In init/initramfs.c (ffffffff838b3a98)
Location: init/initramfs.c:646
Inline: True
Inline callers:
  - init/initramfs.c:do_populate_rootfs
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
In init/initramfs.c (ffff800011433540)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (c1503660)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (c0000000013472f8)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (0)
Location: init/initramfs.c:560
Inline: True
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
In init/initramfs.c (ffffffff8288d2ed)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (ffffffff8288b26a)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (ffffffff828a02ed)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
In init/initramfs.c (ffffffff828a02f2)
Location: init/initramfs.c:537
Inline: True
Inline callers:
  - init/initramfs.c:populate_rootfs
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
</ul>
