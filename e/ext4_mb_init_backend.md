# Function: <code>ext4_mb_init_backend</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff812d35d6)
Location: fs/ext4/mballoc.c:2476
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81302d42)
Location: fs/ext4/mballoc.c:2484
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81318ce3)
Location: fs/ext4/mballoc.c:2484
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8130fc7e)
Location: fs/ext4/mballoc.c:2498
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81334b55)
Location: fs/ext4/mballoc.c:2498
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81362de5)
Location: fs/ext4/mballoc.c:2468
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8137aff5)
Location: fs/ext4/mballoc.c:2468
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a5193)
Location: fs/ext4/mballoc.c:2468
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813be003)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81409da0)
Location: fs/ext4/mballoc.c:2599
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81409da0-ffffffff81409f47: ext4_mb_init_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff8141cb90)
Location: fs/ext4/mballoc.c:2675
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff8141cb90-ffffffff8141ce42: ext4_mb_init_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff81423200)
Location: fs/ext4/mballoc.c:3178
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81423200-ffffffff814234ae: ext4_mb_init_backend (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3198
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81476a40-ffffffff81476d1c: ext4_mb_init_backend (STB_LOCAL)
ffffffff81ccc251-ffffffff81ccc29d: ext4_mb_init_backend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3195
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff814f8d70-ffffffff814f9065: ext4_mb_init_backend (STB_LOCAL)
ffffffff81e7f241-ffffffff81e7f285: ext4_mb_init_backend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3145
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff815934c0-ffffffff815937b5: ext4_mb_init_backend (STB_LOCAL)
ffffffff8206f759-ffffffff8206f79d: ext4_mb_init_backend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3361
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff815ca520-ffffffff815ca7c3: ext4_mb_init_backend (STB_LOCAL)
ffffffff820ef360-ffffffff820ef37f: ext4_mb_init_backend.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_mb_init_backend(struct super_block *sb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/mballoc.c (0)
Location: fs/ext4/mballoc.c:3387
Inline: False
Direct callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
**Symbols:**

```
ffffffff81603330-ffffffff816035d3: ext4_mb_init_backend (STB_LOCAL)
ffffffff821cc48d-ffffffff821cc4ac: ext4_mb_init_backend.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffff800010494c24)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0656694)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (c0000000005be1c4)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffe000319838)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b65e3)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813a7073)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813b3e43)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/mballoc.c (ffffffff813c8a03)
Location: fs/ext4/mballoc.c:2477
Inline: True
Inline callers:
  - fs/ext4/mballoc.c:ext4_mb_init
```
</details>
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
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
