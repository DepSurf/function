# Function: <code>zero_fd_set</code>

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
In fs/select.c (ffffffff812219b3)
Location: include/linux/poll.h:149
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat.c (ffffffff8126529d)
Location: include/linux/poll.h:149
Inline: True
Inline callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff81249672)
Location: include/linux/poll.h:149
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat.c (ffffffff812915bb)
Location: include/linux/poll.h:149
Inline: True
Inline callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff8125c66c)
Location: include/linux/poll.h:149
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
```
In fs/compat.c (ffffffff812a634b)
Location: include/linux/poll.h:149
Inline: True
Inline callers:
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
  - fs/compat.c:compat_core_sys_select
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
In fs/select.c (ffffffff8126956b)
Location: fs/select.c:383
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8128be1b)
Location: fs/select.c:382
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812b2611)
Location: fs/select.c:381
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812c7721)
Location: fs/select.c:406
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812e42aa)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812f5cea)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8132e32d)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff81339bb3)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff81340158)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8138db28)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff8140eec6)
Location: fs/select.c:409
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff81499a66)
Location: fs/select.c:409
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff814ceb36)
Location: fs/select.c:409
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff81501476)
Location: fs/select.c:409
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffff8000103a2e64)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (c0586188)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (c00000000049cb40)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffe00026b5f0)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812ee2ca)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812deefa)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812ec0da)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
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
In fs/select.c (ffffffff812fd0d5)
Location: fs/select.c:408
Inline: True
Inline callers:
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_core_sys_select
  - fs/select.c:compat_get_fd_set
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
  - fs/select.c:core_sys_select
```
</details>
</li>
</ul>

## Differences
