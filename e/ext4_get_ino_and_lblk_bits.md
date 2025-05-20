# Function: <code>ext4_get_ino_and_lblk_bits</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8141d150)
Location: fs/ext4/super.c:1402
Inline: False
```
**Symbols:**

```
ffffffff8141d150-ffffffff8141d167: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81433790)
Location: fs/ext4/super.c:1567
Inline: False
```
**Symbols:**

```
ffffffff81433790-ffffffff814337a7: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff81439f70)
Location: fs/ext4/super.c:1576
Inline: False
```
**Symbols:**

```
ffffffff81439f70-ffffffff81439f87: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/super.c (ffffffff8148dbf0)
Location: fs/ext4/super.c:1562
Inline: False
```
**Symbols:**

```
ffffffff8148dbf0-ffffffff8148dc07: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff8153c740)
Location: fs/ext4/crypto.c:231
Inline: False
```
**Symbols:**

```
ffffffff8153c740-ffffffff8153c75f: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff815dae90)
Location: fs/ext4/crypto.c:231
Inline: False
```
**Symbols:**

```
ffffffff815dae90-ffffffff815daeaf: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_get_ino_and_lblk_bits(struct super_block *sb, int *ino_bits_ret, int *lblk_bits_ret);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/crypto.c (ffffffff81612940)
Location: fs/ext4/crypto.c:231
Inline: False
```
**Symbols:**

```
ffffffff81612940-ffffffff8161295f: ext4_get_ino_and_lblk_bits (STB_LOCAL)
```
</details>
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
</ul>
