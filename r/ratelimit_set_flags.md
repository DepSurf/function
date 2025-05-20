# Function: <code>ratelimit_set_flags</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ddd2a)
Location: include/linux/ratelimit.h:68
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
In kernel/printk/printk.c (ffffffff810e433a)
Location: include/linux/ratelimit.h:68
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
In kernel/printk/printk.c (ffffffff810e25ba)
Location: include/linux/ratelimit.h:68
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
In kernel/printk/printk.c (ffffffff810ea39a)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8109bfa7)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff810f294a)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a41a7)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff810fdf8a)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff812eced8)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8e85)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff811066ba)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff8130e684)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810af455)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff81112a4a)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff813216a4)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b7165)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8111e30d)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff8135b7b3)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b2325)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff81118d9b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff81369d83)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b3965)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8111934b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff81370ab0)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff832aceba)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff810c5b3b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8113970b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff813bf792)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff8345dc70)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff810dd133)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8115c1db)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff81444b20)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff83e7ec75)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff810fd453)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8118ec6b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff814d3f34)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff836a19d5)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff81109483)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff811a03fb)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff81509744)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/intel.c (ffffffff838d1ad5)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/intel.c:sld_state_setup
```
```
In kernel/user.c (ffffffff81112e1b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff811af41b)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff8153e4e1)
Location: include/linux/ratelimit.h:38
Inline: True
Inline callers:
  - fs/buffer.c:__find_get_block_slow
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffff80001010a58c)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffff8000101732d8)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffff8000103d9fc0)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (c0363588)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (c03c56d0)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (c05b34c4)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (c000000000151598)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (c0000000001cdc18)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (c0000000004dedd4)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffe0000ccfd0)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffe00010f154)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffe000292cae)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a97c5)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8110b02a)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff81319c84)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff8109817f)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff810fbeba)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff8130a833)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810a8d25)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff81108f1a)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff81317754)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user.c (ffffffff810b0e15)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/user.c:alloc_uid
```
```
In kernel/printk/printk.c (ffffffff8111414a)
Location: include/linux/ratelimit.h:69
Inline: True
Inline callers:
  - kernel/printk/printk.c:devkmsg_open
```
```
In fs/buffer.c (ffffffff8132935b)
Location: include/linux/ratelimit.h:69
Inline: True
```
</details>
</li>
</ul>

## Differences
