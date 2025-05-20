# Function: <code>__shm_close</code>

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
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __shm_close(struct shm_file_data *sfd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:368
Inline: False
Direct callers:
  - ipc/shm.c:shm_mmap
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff81646b00-ffffffff81646c65: __shm_close (STB_LOCAL)
ffffffff82072f75-ffffffff82072f8a: __shm_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __shm_close(struct shm_file_data *sfd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:368
Inline: False
Direct callers:
  - ipc/shm.c:shm_mmap
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff8167f030-ffffffff8167f195: __shm_close (STB_LOCAL)
ffffffff820f2bbd-ffffffff820f2bd2: __shm_close.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __shm_close(struct shm_file_data *sfd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:369
Inline: False
Direct callers:
  - ipc/shm.c:shm_mmap
  - ipc/shm.c:shm_close
```
**Symbols:**

```
ffffffff816bb420-ffffffff816bb585: __shm_close (STB_LOCAL)
ffffffff821cfe55-ffffffff821cfe6a: __shm_close.cold (STB_LOCAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
