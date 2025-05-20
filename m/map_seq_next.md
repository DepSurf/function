# Function: <code>map_seq_next</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811bfe40)
Location: kernel/bpf/inode.c:195
Inline: False
```
**Symbols:**

```
ffffffff811bfe40-ffffffff811bfec0: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811d1290)
Location: kernel/bpf/inode.c:195
Inline: False
```
**Symbols:**

```
ffffffff811d1290-ffffffff811d1310: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e5600)
Location: kernel/bpf/inode.c:192
Inline: False
```
**Symbols:**

```
ffffffff811e5600-ffffffff811e5681: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f1d00)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffffffff811f1d00-ffffffff811f1d79: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81213950)
Location: kernel/bpf/inode.c:214
Inline: False
```
**Symbols:**

```
ffffffff81213950-ffffffff812139c3: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff812152e0)
Location: kernel/bpf/inode.c:215
Inline: False
```
**Symbols:**

```
ffffffff812152e0-ffffffff81215358: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff81217ff0)
Location: kernel/bpf/inode.c:216
Inline: False
```
**Symbols:**

```
ffffffff81217ff0-ffffffff81218068: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (0)
Location: kernel/bpf/inode.c:216
Inline: False
```
**Symbols:**

```
ffffffff8124e940-ffffffff8124e9dc: map_seq_next (STB_LOCAL)
ffffffff81cb8ff8-ffffffff81cb900d: map_seq_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (0)
Location: kernel/bpf/inode.c:216
Inline: False
```
**Symbols:**

```
ffffffff81295ab0-ffffffff81295b6c: map_seq_next (STB_LOCAL)
ffffffff81e6a2b1-ffffffff81e6a2c6: map_seq_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (0)
Location: kernel/bpf/inode.c:216
Inline: False
```
**Symbols:**

```
ffffffff812f08b0-ffffffff812f096c: map_seq_next (STB_LOCAL)
ffffffff820613b3-ffffffff820613c8: map_seq_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (0)
Location: kernel/bpf/inode.c:216
Inline: False
```
**Symbols:**

```
ffffffff8131d2d0-ffffffff8131d38f: map_seq_next (STB_LOCAL)
ffffffff820e0859-ffffffff820e086e: map_seq_next.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/bpf/inode.c (0)
Location: kernel/bpf/inode.c:213
Inline: False
```
**Symbols:**

```
ffffffff8133f650-ffffffff8133f70f: map_seq_next (STB_LOCAL)
ffffffff821bcf52-ffffffff821bcf67: map_seq_next.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffff800010275308)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffff800010275308-ffff8000102753c0: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c04a7b1c)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
c04a7b1c-c04a7bac: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (c00000000031d2e0)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
c00000000031d2e0-c00000000031d3e8: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffe0001ada96)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffffffe0001ada96-ffffffe0001adb0e: map_seq_next (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811ea320)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffffffff811ea320-ffffffff811ea399: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811dd0e0)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffffffff811dd0e0-ffffffff811dd159: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811e80f0)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffffffff811e80f0-ffffffff811e8169: map_seq_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *map_seq_next(struct seq_file *m, void *v, loff_t *pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/inode.c (ffffffff811f64a0)
Location: kernel/bpf/inode.c:193
Inline: False
```
**Symbols:**

```
ffffffff811f64a0-ffffffff811f6519: map_seq_next (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
