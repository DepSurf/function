# Function: <code>parse_mount_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8128dab0)
Location: fs/devpts/inode.c:162
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
  - fs/devpts/inode.c:devpts_mount
```
**Symbols:**

```
ffffffff8128dab0-ffffffff8128dca2: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812bb0e0)
Location: fs/devpts/inode.c:190
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_mount
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff812bb0e0-ffffffff812bb2df: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812d08f0)
Location: fs/devpts/inode.c:190
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff812d08f0-ffffffff812d0aef: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812e1e80)
Location: fs/devpts/inode.c:223
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff812e1e80-ffffffff812e206b: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81306860)
Location: fs/devpts/inode.c:251
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81306860-ffffffff81306a52: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:251
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81334870-ffffffff81334a51: parse_mount_options (STB_LOCAL)
ffffffff81335263-ffffffff81335274: parse_mount_options.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8134bb90)
Location: fs/devpts/inode.c:249
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff8134bb90-ffffffff8134bd95: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81374550-ffffffff81374762: parse_mount_options (STB_LOCAL)
ffffffff81374efa-ffffffff81374f0b: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff8138c7d0-ffffffff8138c9e2: parse_mount_options (STB_LOCAL)
ffffffff8138d17a-ffffffff8138d18b: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff813d7bf0-ffffffff813d7de7: parse_mount_options (STB_LOCAL)
ffffffff813d8611-ffffffff813d8622: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff813e9890-ffffffff813e9a87: parse_mount_options (STB_LOCAL)
ffffffff81bec1b5-ffffffff81bec1c6: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff813f03f0-ffffffff813f05fc: parse_mount_options (STB_LOCAL)
ffffffff81bde213-ffffffff81bde224: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff814422e0-ffffffff814424ec: parse_mount_options (STB_LOCAL)
ffffffff81cc87ea-ffffffff81cc87fb: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff814be020-ffffffff814be267: parse_mount_options (STB_LOCAL)
ffffffff81e7b535-ffffffff81e7b546: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81555df0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81555df0-ffffffff81556030: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8158db90)
Location: fs/devpts/inode.c:228
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff8158db90-ffffffff8158ddd4: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff815c68d0)
Location: fs/devpts/inode.c:227
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_fill_super
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff815c68d0-ffffffff815c6b14: parse_mount_options (STB_LOCAL)
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
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffff80001045e360)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffff80001045e360-ffff80001045e56c: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c061edac)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
c061edac-c061efdc: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c00000000057a270)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
c00000000057a270-c00000000057a520: parse_mount_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffe0002ee098)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffe0002ee098-ffffffe0002ee260: parse_mount_options (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81384db0-ffffffff81384fc2: parse_mount_options (STB_LOCAL)
ffffffff8138575a-ffffffff8138576b: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81375840-ffffffff81375a52: parse_mount_options (STB_LOCAL)
ffffffff813761ea-ffffffff813761fb: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff81382880-ffffffff81382a92: parse_mount_options (STB_LOCAL)
ffffffff8138322a-ffffffff8138323b: parse_mount_options.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int parse_mount_options(char *data, int op, struct pts_mount_opts *opts);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/devpts/inode.c (0)
Location: fs/devpts/inode.c:246
Inline: False
Direct callers:
  - fs/devpts/inode.c:devpts_remount
```
**Symbols:**

```
ffffffff813963a0-ffffffff813965b2: parse_mount_options (STB_LOCAL)
ffffffff81396d4a-ffffffff81396d5b: parse_mount_options.cold (STB_LOCAL)
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
