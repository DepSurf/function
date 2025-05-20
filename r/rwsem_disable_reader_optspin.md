# Function: <code>rwsem_disable_reader_optspin</code>

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
In kernel/locking/rwsem.c (ffffffff810f83d6)
Location: kernel/locking/rwsem.c:1114
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff81104206)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff8110ee07)
Location: kernel/locking/rwsem.c:1123
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffff800010169a8c)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (c03b5d28)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (c0000000001c19bc)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffe00010ad34)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff810fd516)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff810ed722)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff810fa6d6)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
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
In kernel/locking/rwsem.c (ffffffff811058ad)
Location: kernel/locking/rwsem.c:1126
Inline: True
Inline callers:
  - kernel/locking/rwsem.c:rwsem_down_write_slowpath
```
</details>
</li>
</ul>

## Differences
