# Function: <code>d_instantiate_no_diralias</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int d_instantiate_no_diralias(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff81224580)
Location: fs/dcache.c:1868
Inline: False
```
**Symbols:**

```
ffffffff81224580-ffffffff8122460a: d_instantiate_no_diralias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int d_instantiate_no_diralias(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8124b480)
Location: fs/dcache.c:1829
Inline: False
```
**Symbols:**

```
ffffffff8124b480-ffffffff8124b504: d_instantiate_no_diralias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int d_instantiate_no_diralias(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8125e460)
Location: fs/dcache.c:1838
Inline: False
```
**Symbols:**

```
ffffffff8125e460-ffffffff8125e4e4: d_instantiate_no_diralias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int d_instantiate_no_diralias(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8126bcc0)
Location: fs/dcache.c:1868
Inline: False
```
**Symbols:**

```
ffffffff8126bcc0-ffffffff8126bd44: d_instantiate_no_diralias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int d_instantiate_no_diralias(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff8128e550)
Location: fs/dcache.c:1880
Inline: False
```
**Symbols:**

```
ffffffff8128e550-ffffffff8128e5d4: d_instantiate_no_diralias (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int d_instantiate_no_diralias(struct dentry *entry, struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/dcache.c (ffffffff812b6590)
Location: fs/dcache.c:1910
Inline: True
```
**Symbols:**

```
ffffffff812b6590-ffffffff812b6614: d_instantiate_no_diralias (STB_GLOBAL)
```
</details>
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
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
