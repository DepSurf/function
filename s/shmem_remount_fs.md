# Function: <code>shmem_remount_fs</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811a6d50)
Location: mm/shmem.c:2861
Inline: False
```
**Symbols:**

```
ffffffff811a6d50-ffffffff811a6ea8: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811be9b0)
Location: mm/shmem.c:3505
Inline: False
```
**Symbols:**

```
ffffffff811be9b0-ffffffff811beb10: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811cf1a0)
Location: mm/shmem.c:3422
Inline: False
```
**Symbols:**

```
ffffffff811cf1a0-ffffffff811cf357: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811d7ee0)
Location: mm/shmem.c:3572
Inline: False
```
**Symbols:**

```
ffffffff811d7ee0-ffffffff811d802e: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff811ecd60)
Location: mm/shmem.c:3597
Inline: False
```
**Symbols:**

```
ffffffff811ecd60-ffffffff811eceae: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff8120e7c0)
Location: mm/shmem.c:3407
Inline: False
```
**Symbols:**

```
ffffffff8120e7c0-ffffffff8120e907: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff812217c0)
Location: mm/shmem.c:3393
Inline: False
```
**Symbols:**

```
ffffffff812217c0-ffffffff81221907: shmem_remount_fs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int shmem_remount_fs(struct super_block *sb, int *flags, char *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/shmem.c (ffffffff81231030)
Location: mm/shmem.c:3475
Inline: False
```
**Symbols:**

```
ffffffff81231030-ffffffff81231176: shmem_remount_fs (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
