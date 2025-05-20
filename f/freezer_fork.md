# Function: <code>freezer_fork</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void freezer_fork(struct task_struct *task, void *private);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup_freezer.c (ffffffff81119c70)
Location: kernel/cgroup_freezer.c:203
Inline: False
```
**Symbols:**

```
ffffffff81119c70-ffffffff81119cd1: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup_freezer.c (ffffffff81121a80)
Location: kernel/cgroup_freezer.c:203
Inline: False
```
**Symbols:**

```
ffffffff81121a80-ffffffff81121ae1: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cgroup_freezer.c (ffffffff8112a0c0)
Location: kernel/cgroup_freezer.c:203
Inline: False
```
**Symbols:**

```
ffffffff8112a0c0-ffffffff8112a121: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff8112afc0)
Location: kernel/cgroup/freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff8112afc0-ffffffff8112b029: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81137e90)
Location: kernel/cgroup/freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81137e90-ffffffff81137ef9: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff811467b0)
Location: kernel/cgroup/freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff811467b0-ffffffff81146818: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/freezer.c (ffffffff81152380)
Location: kernel/cgroup/freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81152380-ffffffff811523e8: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8115e9e0)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff8115e9e0-ffffffff8115ea4c: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116a640)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff8116a640-ffffffff8116a6ac: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8117c120)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff8117c120-ffffffff8117c180: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81178f60)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81178f60-ffffffff81178fc5: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81179ad0)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81179ad0-ffffffff81179b35: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811a13f0)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff811a13f0-ffffffff811a1455: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff811d1d10)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff811d1d10-ffffffff811d1d8c: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81215a10)
Location: kernel/cgroup/legacy_freezer.c:204
Inline: True
```
**Symbols:**

```
ffffffff81215a10-ffffffff81215a8c: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8122b340)
Location: kernel/cgroup/legacy_freezer.c:209
Inline: True
```
**Symbols:**

```
ffffffff8122b340-ffffffff8122b3bc: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81243300)
Location: kernel/cgroup/legacy_freezer.c:215
Inline: True
```
**Symbols:**

```
ffffffff81243300-ffffffff8124337c: freezer_fork (STB_LOCAL)
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
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffff8000101de190)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffff8000101de190-ffff8000101de204: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (c041fe4c)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
c041fe4c-c041febc: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (c00000000024c000)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
c00000000024c000-c00000000024c0c0: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffe000155854)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffe000155854-ffffffe0001558c8: freezer_fork (STB_LOCAL)
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
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81162c60)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81162c60-ffffffff81162ccc: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81155eb0)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81155eb0-ffffffff81155f1c: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff81160a30)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff81160a30-ffffffff81160a9c: freezer_fork (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void freezer_fork(struct task_struct *task);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/legacy_freezer.c (ffffffff8116ddb0)
Location: kernel/cgroup/legacy_freezer.c:203
Inline: True
```
**Symbols:**

```
ffffffff8116ddb0-ffffffff8116de18: freezer_fork (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>void *private</code>
</li>
</ul>
</details>
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
