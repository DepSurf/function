# Function: <code>choose_mountpoint_rcu</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81321af5)
Location: fs/namei.c:1125
Inline: True
Inline callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:choose_mountpoint
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c0e0)
Location: fs/namei.c:1125
Inline: False
Direct callers:
  - fs/namei.c:follow_dotdot_rcu
  - fs/namei.c:choose_mountpoint
```
**Symbols:**

```
ffffffff8132c0e0-ffffffff8132c13a: choose_mountpoint_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332120)
Location: fs/namei.c:1210
Inline: False
```
**Symbols:**

```
ffffffff81332120-ffffffff8133217a: choose_mountpoint_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8137f8b0)
Location: fs/namei.c:1238
Inline: False
```
**Symbols:**

```
ffffffff8137f8b0-ffffffff8137f90a: choose_mountpoint_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813ffa30)
Location: fs/namei.c:1282
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff813ffa30-ffffffff813ffaa8: choose_mountpoint_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814899f0)
Location: fs/namei.c:1290
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:follow_dotdot_rcu
```
**Symbols:**

```
ffffffff814899f0-ffffffff81489a68: choose_mountpoint_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814be920)
Location: fs/namei.c:1293
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff814be920-ffffffff814be998: choose_mountpoint_rcu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool choose_mountpoint_rcu(struct mount *m, const struct path *root, struct path *path, unsigned int *seqp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f0da0)
Location: fs/namei.c:1296
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:handle_dots
```
**Symbols:**

```
ffffffff814f0da0-ffffffff814f0e18: choose_mountpoint_rcu (STB_LOCAL)
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
