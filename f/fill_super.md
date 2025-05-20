# Function: <code>fill_super</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8133fc60)
Location: security/inode.c:28
Inline: False
```
**Symbols:**

```
ffffffff8133fc60-ffffffff8133fc7c: fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81375280)
Location: security/inode.c:28
Inline: False
```
**Symbols:**

```
ffffffff81375280-ffffffff8137529c: fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff8138bbb0)
Location: security/inode.c:28
Inline: False
```
**Symbols:**

```
ffffffff8138bbb0-ffffffff8138bbcc: fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision ⚠️</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813a1850)
Location: security/inode.c:42
Inline: False
```
```
In security/apparmor/apparmorfs.c (ffffffff813d8980)
Location: security/apparmor/apparmorfs.c:143
Inline: False
```
**Symbols:**

```
ffffffff813a1850-ffffffff813a187d: fill_super (STB_LOCAL)
ffffffff813d8980-ffffffff813d89ad: fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision ⚠️</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813c7650)
Location: security/inode.c:42
Inline: False
```
```
In security/apparmor/apparmorfs.c (ffffffff813fecb0)
Location: security/apparmor/apparmorfs.c:143
Inline: False
```
**Symbols:**

```
ffffffff813c7650-ffffffff813c767d: fill_super (STB_LOCAL)
ffffffff813fecb0-ffffffff813fecdd: fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff813f6c90)
Location: security/inode.c:42
Inline: False
```
```
In security/apparmor/apparmorfs.c (ffffffff8142fbb0)
Location: security/apparmor/apparmorfs.c:140
Inline: False
```
**Symbols:**

```
ffffffff813f6c90-ffffffff813f6cbd: fill_super (STB_LOCAL)
ffffffff8142fbb0-ffffffff8142fbdd: fill_super (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int fill_super(struct super_block *sb, void *data, int silent);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/inode.c (ffffffff81412740)
Location: security/inode.c:43
Inline: False
```
```
In security/apparmor/apparmorfs.c (ffffffff8144c710)
Location: security/apparmor/apparmorfs.c:140
Inline: False
```
**Symbols:**

```
ffffffff81412740-ffffffff8141276d: fill_super (STB_LOCAL)
ffffffff8144c710-ffffffff8144c73d: fill_super (STB_LOCAL)
```
</details>
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
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
