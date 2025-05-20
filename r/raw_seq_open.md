# Function: <code>raw_seq_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int raw_seq_open(struct inode *ino, struct file *file, struct raw_hashinfo *h, const struct seq_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817848c0)
Location: net/ipv4/raw.c:1056
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_seq_open
Direct callers:
  - net/ipv6/raw.c:raw6_seq_open
```
**Symbols:**

```
ffffffff817848c0-ffffffff817848fc: raw_seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int raw_seq_open(struct inode *ino, struct file *file, struct raw_hashinfo *h, const struct seq_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff817f1ed6)
Location: net/ipv4/raw.c:1059
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_seq_open
Direct callers:
  - net/ipv6/raw.c:raw6_seq_open
```
**Symbols:**

```
ffffffff817f1e90-ffffffff817f1ecc: raw_seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int raw_seq_open(struct inode *ino, struct file *file, struct raw_hashinfo *h, const struct seq_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff81822cc6)
Location: net/ipv4/raw.c:1078
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_seq_open
Direct callers:
  - net/ipv6/raw.c:raw6_seq_open
```
**Symbols:**

```
ffffffff81822c80-ffffffff81822cb9: raw_seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int raw_seq_open(struct inode *ino, struct file *file, struct raw_hashinfo *h, const struct seq_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818438a6)
Location: net/ipv4/raw.c:1087
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_seq_open
Direct callers:
  - net/ipv6/raw.c:raw6_seq_open
```
**Symbols:**

```
ffffffff81843860-ffffffff81843899: raw_seq_open (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int raw_seq_open(struct inode *ino, struct file *file, struct raw_hashinfo *h, const struct seq_operations *ops);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/raw.c (ffffffff818c32a6)
Location: net/ipv4/raw.c:1100
Inline: True
Inline callers:
  - net/ipv4/raw.c:raw_v4_seq_open
Direct callers:
  - net/ipv6/raw.c:raw6_seq_open
```
**Symbols:**

```
ffffffff818c3260-ffffffff818c3299: raw_seq_open (STB_GLOBAL)
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
