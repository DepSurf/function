# Function: <code>shmem_fcntl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int shmem_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ab990)
Location: mm/shmem.c:2071
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff811ab990-ffffffff811ab9e9: shmem_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int shmem_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811c42e0)
Location: mm/shmem.c:2741
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff811c42e0-ffffffff811c4339: shmem_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int shmem_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d43e0)
Location: mm/shmem.c:2646
Inline: False
Direct callers:
  - fs/fcntl.c:SyS_fcntl
```
**Symbols:**

```
ffffffff811d43e0-ffffffff811d4439: shmem_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int shmem_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811dd030)
Location: mm/shmem.c:2815
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff811dd030-ffffffff811dd082: shmem_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int shmem_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811f2a80)
Location: mm/shmem.c:2842
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff811f2a80-ffffffff811f2ad2: shmem_fcntl (STB_GLOBAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
