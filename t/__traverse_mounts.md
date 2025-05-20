# Function: <code>__traverse_mounts</code>

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
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81320c70)
Location: fs/namei.c:1207
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff81320c70-ffffffff81320e9a: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c200)
Location: fs/namei.c:1207
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff8132c200-ffffffff8132c42a: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332240)
Location: fs/namei.c:1292
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff81332240-ffffffff8133246a: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8137f9d0)
Location: fs/namei.c:1320
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff8137f9d0-ffffffff8137fbfa: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813ffc30)
Location: fs/namei.c:1364
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff813ffc30-ffffffff813ffe42: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489c40)
Location: fs/namei.c:1372
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff81489c40-ffffffff81489e52: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bec30)
Location: fs/namei.c:1375
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff814bec30-ffffffff814bee41: __traverse_mounts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __traverse_mounts(struct path *path, unsigned int flags, bool *jumped, int *count, unsigned int lookup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f10b0)
Location: fs/namei.c:1378
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:follow_down
```
**Symbols:**

```
ffffffff814f10b0-ffffffff814f12c1: __traverse_mounts (STB_LOCAL)
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
