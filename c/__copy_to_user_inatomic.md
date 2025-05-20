# Function: <code>__copy_to_user_inatomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/maccess.c (ffffffff811915c6)
Location: arch/x86/include/asm/uaccess_64.h:211
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
```
```
In lib/iov_iter.c (ffffffff813fd95d)
Location: arch/x86/include/asm/uaccess_64.h:211
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_page_to_iter_iovec
  - lib/iov_iter.c:copy_page_to_iter_iovec
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
In mm/maccess.c (ffffffff811a5dc0)
Location: arch/x86/include/asm/uaccess_64.h:255
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff811b6140)
Location: arch/x86/include/asm/uaccess_64.h:255
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff811be08c)
Location: include/linux/uaccess.h:91
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff811d2d4d)
Location: include/linux/uaccess.h:92
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff811f40cd)
Location: include/linux/uaccess.h:92
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff8120645d)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff8121d74d)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff8122b1de)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff812580cb)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff812627dd)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff8126723d)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff812a3c7d)
Location: include/linux/uaccess.h:131
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff812fbd24)
Location: include/linux/uaccess.h:91
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff81365f04)
Location: include/linux/uaccess.h:99
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff8139836b)
Location: include/linux/uaccess.h:121
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffffffff813c218b)
Location: include/linux/uaccess.h:121
Inline: True
Inline callers:
  - mm/maccess.c:copy_to_user_nofault
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
In mm/maccess.c (ffff8000102b9838)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (c04e5cc0)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (c0000000003717e0)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffe0001dd118)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff8122382e)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff812169de)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff812215ce)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
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
In mm/maccess.c (ffffffff8123078e)
Location: include/linux/uaccess.h:89
Inline: True
Inline callers:
  - mm/maccess.c:__probe_user_write
  - mm/maccess.c:__probe_kernel_write
```
</details>
</li>
</ul>

## Differences
