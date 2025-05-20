# Function: <code>rwsem_reader_phase_trylock</code>

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
In kernel/locking/rwsem.c (ffffffff81a9b293)
Location: kernel/locking/rwsem.c:942
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (ffffffff81ad2be3)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (ffffffff81bcac35)
Location: kernel/locking/rwsem.c:944
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (ffff800010da5088)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (c0e9d218)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (c000000000ee7840)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
Location: kernel/locking/rwsem.c:977
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
In kernel/locking/rwsem.c (ffffffff81a71a53)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (ffffffff81a2de2b)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (ffffffff81adde63)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
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
In kernel/locking/rwsem.c (ffffffff81aea30a)
Location: kernel/locking/rwsem.c:947
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_read_slowpath
```
</details>
</li>
</ul>

## Differences
