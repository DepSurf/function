# Function: <code>io_should_wake</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81340481)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff81386c34)
Location: fs/io_uring.c:6269
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff8139210b)
Location: fs/io_uring.c:7192
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff81395763)
Location: fs/io_uring.c:6973
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff813e5839)
Location: fs/io_uring.c:7555
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In io_uring/io_uring.c (ffffffff816cf90a)
Location: io_uring/io_uring.c:8860
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wake_function
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
In io_uring/io_uring.c (ffffffff81791cd1)
Location: io_uring/io_uring.c:2436
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wake_function
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
In io_uring/io_uring.c (ffffffff817d0e22)
Location: io_uring/io_uring.c:2461
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wake_function
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
In io_uring/io_uring.c (ffffffff81813976)
Location: io_uring/io_uring.c:2492
Inline: True
Inline callers:
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_cqring_wait
  - io_uring/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffff800010405b68)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:__arm64_sys_io_uring_enter
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (c05d7340)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (c00000000050e854)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffe0002b0f32)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:__se_sys_io_uring_enter
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff81338a61)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff81329791)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff81336531)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
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
In fs/io_uring.c (ffffffff81349601)
Location: fs/io_uring.c:2929
Inline: True
Inline callers:
  - fs/io_uring.c:io_cqring_wait
  - fs/io_uring.c:io_wake_function
```
</details>
</li>
</ul>

## Differences
