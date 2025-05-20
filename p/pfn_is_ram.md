# Function: <code>pfn_is_ram</code>

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
In fs/proc/vmcore.c (ffffffff81287593)
Location: fs/proc/vmcore.c:69
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812b4d65)
Location: fs/proc/vmcore.c:69
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812ca5f5)
Location: fs/proc/vmcore.c:69
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812d7bf8)
Location: fs/proc/vmcore.c:69
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff812fc2d8)
Location: fs/proc/vmcore.c:69
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81329df9)
Location: fs/proc/vmcore.c:81
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (ffffffff81340c29)
Location: fs/proc/vmcore.c:83
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813685b2)
Location: fs/proc/kcore.c:71
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81368ff3)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8138081f)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81381253)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813caae0)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff813cb49b)
Location: fs/proc/vmcore.c:87
Inline: True
Inline callers:
  - fs/proc/vmcore.c:remap_oldmem_pfn_checked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813dc7a0)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff813dd14b)
Location: fs/proc/vmcore.c:87
Inline: True
Inline callers:
  - fs/proc/vmcore.c:remap_oldmem_pfn_checked
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813e366b)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff813e433e)
Location: fs/proc/vmcore.c:87
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81435428)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81435eee)
Location: fs/proc/vmcore.c:87
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff814af4a2)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff814b030e)
Location: fs/proc/vmcore.c:105
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81545d67)
Location: fs/proc/kcore.c:71
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81546bb8)
Location: fs/proc/vmcore.c:104
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8157d8bc)
Location: fs/proc/kcore.c:71
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/vmcore.c (ffffffff8157e697)
Location: fs/proc/vmcore.c:104
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff815b62dc)
Location: fs/proc/kcore.c:71
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore_iter
```
```
In fs/proc/vmcore.c (ffffffff815b70d7)
Location: fs/proc/vmcore.c:104
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffff80001044e45c)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffff80001044ef28)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/vmcore.c (c0612460)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (c000000000565c0c)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (c000000000566afc)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
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
In fs/proc/kcore.c (ffffffe0002e2882)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff81378dff)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81379833)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813698cf)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff8136a303)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff813768cf)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff81377303)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Full Inline ⚠️</summary>

**Collision:** Static-Static Collision

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/kcore.c (ffffffff8138a37f)
Location: fs/proc/kcore.c:72
Inline: True
Inline callers:
  - fs/proc/kcore.c:read_kcore
```
```
In fs/proc/vmcore.c (ffffffff8138adb3)
Location: fs/proc/vmcore.c:88
Inline: True
Inline callers:
  - fs/proc/vmcore.c:mmap_vmcore
```
</details>
</li>
</ul>

## Differences
