# Function: <code>is_unprivileged_user</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff8127c960)
Location: fs/pipe.c:621
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff8127c960-ffffffff8127c98c: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812a38b0)
Location: fs/pipe.c:620
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812a38b0-ffffffff812a38e0: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812b8a60)
Location: fs/pipe.c:634
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812b8a60-ffffffff812b8a90: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d55d0)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812d55d0-ffffffff812d55fe: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812e7140)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812e7140-ffffffff812e716e: is_unprivileged_user (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffff80001038f8f8)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffff80001038f8f8-ffff80001038f944: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c057682c)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
c057682c-c057686c: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (c000000000487550)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
c000000000487550-c0000000004875c8: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffe00025f7f4)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffe00025f7f4-ffffffe00025f838: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812df720)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812df720-ffffffff812df74e: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812d0360)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812d0360-ffffffff812d038e: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812dd530)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812dd530-ffffffff812dd55e: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool is_unprivileged_user();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/pipe.c (ffffffff812ee4b0)
Location: fs/pipe.c:646
Inline: False
Direct callers:
  - fs/pipe.c:pipe_fcntl
  - fs/pipe.c:alloc_pipe_info
  - fs/pipe.c:alloc_pipe_info
```
**Symbols:**

```
ffffffff812ee4b0-ffffffff812ee4de: is_unprivileged_user (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
