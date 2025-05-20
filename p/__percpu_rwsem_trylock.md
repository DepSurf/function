# Function: <code>__percpu_rwsem_trylock</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8110f252)
Location: kernel/locking/percpu-rwsem.c:90
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
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
In kernel/locking/percpu-rwsem.c (ffffffff8110c412)
Location: kernel/locking/percpu-rwsem.c:90
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
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
In kernel/locking/percpu-rwsem.c (ffffffff8110e252)
Location: kernel/locking/percpu-rwsem.c:90
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
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
In kernel/locking/percpu-rwsem.c (ffffffff8112d9a2)
Location: kernel/locking/percpu-rwsem.c:90
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8114eb5e)
Location: kernel/locking/percpu-rwsem.c:92
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
**Symbols:**

```
ffffffff8114e970-ffffffff8114e9cf: __percpu_rwsem_trylock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8117dd0e)
Location: kernel/locking/percpu-rwsem.c:92
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
**Symbols:**

```
ffffffff8117db00-ffffffff8117db5f: __percpu_rwsem_trylock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8118e9ae)
Location: kernel/locking/percpu-rwsem.c:92
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
**Symbols:**

```
ffffffff8118e7a0-ffffffff8118e7ff: __percpu_rwsem_trylock.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/locking/percpu-rwsem.c (ffffffff8119d35e)
Location: kernel/locking/percpu-rwsem.c:92
Inline: True
Inline callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
Direct callers:
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wait
  - kernel/locking/percpu-rwsem.c:percpu_rwsem_wake_function
```
**Symbols:**

```
ffffffff8119d150-ffffffff8119d1af: __percpu_rwsem_trylock.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
