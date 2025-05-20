# Function: <code>hook_sb_delete</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hook_sb_delete(const struct super_block * sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff81538d80)
Location: security/landlock/fs.c:344
Inline: True
```
**Symbols:**

```
ffffffff81538d80-ffffffff81538fa4: hook_sb_delete.part.0 (STB_LOCAL)
ffffffff81538fb0-ffffffff81538fca: hook_sb_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hook_sb_delete(const struct super_block * sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff815975a0)
Location: security/landlock/fs.c:344
Inline: True
```
**Symbols:**

```
ffffffff815975a0-ffffffff815977c4: hook_sb_delete.part.0 (STB_LOCAL)
ffffffff815977d0-ffffffff81597801: hook_sb_delete (STB_LOCAL)
ffffffff81cd6bc2-ffffffff81cd6bd6: hook_sb_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hook_sb_delete(const struct super_block * sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff816393d0)
Location: security/landlock/fs.c:912
Inline: True
```
**Symbols:**

```
ffffffff816393d0-ffffffff8163962e: hook_sb_delete.part.0 (STB_LOCAL)
ffffffff81639630-ffffffff8163966c: hook_sb_delete (STB_LOCAL)
ffffffff81e89aba-ffffffff81e89acf: hook_sb_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hook_sb_delete(const struct super_block * sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff816f0a40)
Location: security/landlock/fs.c:927
Inline: True
```
**Symbols:**

```
ffffffff816f0a40-ffffffff816f0c9e: hook_sb_delete.part.0 (STB_LOCAL)
ffffffff816f0cb0-ffffffff816f0cec: hook_sb_delete (STB_LOCAL)
ffffffff82074efd-ffffffff82074f12: hook_sb_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hook_sb_delete(const struct super_block * sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff8172aee0)
Location: security/landlock/fs.c:927
Inline: True
```
**Symbols:**

```
ffffffff8172aee0-ffffffff8172b13e: hook_sb_delete.part.0 (STB_LOCAL)
ffffffff8172b150-ffffffff8172b18c: hook_sb_delete (STB_LOCAL)
ffffffff820f4acb-ffffffff820f4ae0: hook_sb_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void hook_sb_delete(const struct super_block * sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/landlock/fs.c (ffffffff8176ca00)
Location: security/landlock/fs.c:844
Inline: True
```
**Symbols:**

```
ffffffff8176ca00-ffffffff8176cc5e: hook_sb_delete.part.0 (STB_LOCAL)
ffffffff8176cc70-ffffffff8176ccac: hook_sb_delete (STB_LOCAL)
ffffffff821d1f8f-ffffffff821d1fa4: hook_sb_delete.cold (STB_LOCAL)
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
