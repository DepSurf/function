# Function: <code>pde_force_lookup</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/proc/proc_net.c (ffffffff8133f00e)
Location: fs/proc/proc_net.c:51
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff8136736e)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff8137f5ee)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff813c985e)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff813d29f0)
Location: fs/proc/internal.h:314
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff813db4ce)
Location: fs/proc/internal.h:314
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff813d9880)
Location: fs/proc/internal.h:316
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff813e23fe)
Location: fs/proc/internal.h:316
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff8142afb0)
Location: fs/proc/internal.h:316
Inline: True
```
```
In fs/proc/proc_net.c (ffffffff81433f0e)
Location: fs/proc/internal.h:316
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff814a40d6)
Location: fs/proc/internal.h:311
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff814ae07e)
Location: fs/proc/internal.h:311
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff815394e6)
Location: fs/proc/internal.h:316
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff8154463e)
Location: fs/proc/internal.h:316
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff81571726)
Location: fs/proc/internal.h:316
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff8157c23e)
Location: fs/proc/internal.h:316
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/generic.c (ffffffff815aa0d6)
Location: fs/proc/internal.h:314
Inline: True
Inline callers:
  - fs/proc/generic.c:__proc_create
```
```
In fs/proc/proc_net.c (ffffffff815b4b4e)
Location: fs/proc/internal.h:314
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_net_ns_init
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffff80001044cda8)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (c06114b0)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (c0000000005643d8)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffe0002e1afa)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff81377bce)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff8136869e)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff8137569e)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
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
In fs/proc/proc_net.c (ffffffff8138913e)
Location: fs/proc/proc_net.c:52
Inline: True
Inline callers:
  - fs/proc/proc_net.c:proc_create_net_single_write
  - fs/proc/proc_net.c:proc_create_net_single
  - fs/proc/proc_net.c:proc_create_net_data_write
  - fs/proc/proc_net.c:proc_create_net_data
```
</details>
</li>
</ul>

## Differences
