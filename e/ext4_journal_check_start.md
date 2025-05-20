# Function: <code>ext4_journal_check_start</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812cb690)
Location: fs/ext4/ext4_jbd2.c:41
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
```
**Symbols:**

```
ffffffff812cb690-ffffffff812cb70f: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812fafd0)
Location: fs/ext4/ext4_jbd2.c:41
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff812fafd0-ffffffff812fb04f: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81310f70)
Location: fs/ext4/ext4_jbd2.c:41
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81310f70-ffffffff81310fef: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff812e5e50)
Location: fs/ext4/ext4_jbd2.c:41
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff812e5e50-ffffffff812e5ecf: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8130a860)
Location: fs/ext4/ext4_jbd2.c:42
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff8130a860-ffffffff8130a8df: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81338810)
Location: fs/ext4/ext4_jbd2.c:42
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81338810-ffffffff8133888f: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8134fac0)
Location: fs/ext4/ext4_jbd2.c:42
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff8134fac0-ffffffff8134fb3f: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/ext4_jbd2.c (0)
Location: fs/ext4/ext4_jbd2.c:42
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81378750-ffffffff813787da: ext4_journal_check_start (STB_LOCAL)
ffffffff8137906b-ffffffff81379086: ext4_journal_check_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81390b10)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81390b10-ffffffff81390b9a: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813dc1d0)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff813dc1d0-ffffffff813dc262: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813edc60)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff813edc60-ffffffff813edcfb: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813f4240)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff813f4240-ffffffff813f42db: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81446380)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81446380-ffffffff8144641b: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff814c24d0)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff814c24d0-ffffffff814c2586: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8155a730)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff8155a730-ffffffff8155a7e6: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81592550)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81592550-ffffffff81592606: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff815cb270)
Location: fs/ext4/ext4_jbd2.c:64
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff815cb270-ffffffff815cb327: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffff8000104634f0)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffff8000104634f0-ffff800010463598: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (c0623ba0)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
c0623ba0-c0623c54: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (c000000000580550)
Location: fs/ext4/ext4_jbd2.c:42
Inline: False
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
c000000000580550-c000000000580628: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffe0002f1ea8)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffe0002f1ea8-ffffffe0002f1f36: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff813890f0)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff813890f0-ffffffff8138917a: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81379b80)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81379b80-ffffffff81379c0a: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff81386a50)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff81386a50-ffffffff81386ada: ext4_journal_check_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ext4_journal_check_start(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/ext4_jbd2.c (ffffffff8139a730)
Location: fs/ext4/ext4_jbd2.c:42
Inline: True
Direct callers:
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_reserved
  - fs/ext4/ext4_jbd2.c:__ext4_journal_start_sb
```
**Symbols:**

```
ffffffff8139a730-ffffffff8139a7a1: ext4_journal_check_start (STB_LOCAL)
```
</details>
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
