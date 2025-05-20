# Function: <code>clear_wr_nonspinnable</code>

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
In kernel/locking/rwsem.c (ffffffff810f7f30)
Location: kernel/locking/rwsem.c:917
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (ffffffff81103d60)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (ffffffff8110e960)
Location: kernel/locking/rwsem.c:919
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In kernel/locking/rwsem.c (ffff800010169810)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (c03b5880)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (c0000000001c1118)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (0)
Location: kernel/locking/rwsem.c:975
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
In kernel/locking/rwsem.c (ffffffff810fd070)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (ffffffff810ed280)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (ffffffff810fa230)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
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
In kernel/locking/rwsem.c (ffffffff811053a0)
Location: kernel/locking/rwsem.c:922
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:up_read
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
</ul>

## Differences
