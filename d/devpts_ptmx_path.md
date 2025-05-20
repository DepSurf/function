# Function: <code>devpts_ptmx_path</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff812e20b0)
Location: fs/devpts/inode.c:136
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff812e20b0-ffffffff812e20fe: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81306aa0)
Location: fs/devpts/inode.c:136
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81306aa0-ffffffff81306ae0: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81334aa0)
Location: fs/devpts/inode.c:136
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81334aa0-ffffffff81334ae0: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8134bde0)
Location: fs/devpts/inode.c:134
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff8134bde0-ffffffff8134be20: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813747b0)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff813747b0-ffffffff813747f0: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8138ca30)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff8138ca30-ffffffff8138ca70: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813d8287)
Location: fs/devpts/inode.c:131
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813e9f27)
Location: fs/devpts/inode.c:131
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff813f0a67)
Location: fs/devpts/inode.c:131
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81442957)
Location: fs/devpts/inode.c:131
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff814be6d0)
Location: fs/devpts/inode.c:131
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81556530)
Location: fs/devpts/inode.c:131
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff8158e2f6)
Location: fs/devpts/inode.c:113
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff815c7026)
Location: fs/devpts/inode.c:112
Inline: True
Inline callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
  - fs/devpts/inode.c:devpts_mntget
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
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffff80001045e5c8)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffff80001045e5c8-ffff80001045e62c: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c061f020)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
c061f020-c061f078: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (c00000000057a590)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
c00000000057a590-c00000000057a608: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffe0002ee2ae)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffe0002ee2ae-ffffffe0002ee2f6: devpts_ptmx_path (STB_LOCAL)
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
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81385010)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81385010-ffffffff81385050: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81375aa0)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81375aa0-ffffffff81375ae0: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81382ae0)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81382ae0-ffffffff81382b20: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int devpts_ptmx_path(struct path *path);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/devpts/inode.c (ffffffff81396600)
Location: fs/devpts/inode.c:131
Inline: True
Direct callers:
  - fs/devpts/inode.c:devpts_acquire
  - fs/devpts/inode.c:devpts_mntget
```
**Symbols:**

```
ffffffff81396600-ffffffff81396640: devpts_ptmx_path (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
