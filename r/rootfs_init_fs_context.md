# Function: <code>rootfs_init_fs_context</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002be0)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffff81002be0-ffffffff81002c00: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003e40)
Location: init/do_mounts.c:698
Inline: False
```
**Symbols:**

```
ffffffff81003e40-ffffffff81003e60: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003f00)
Location: init/do_mounts.c:630
Inline: False
```
**Symbols:**

```
ffffffff81003f00-ffffffff81003f20: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81003e00)
Location: init/do_mounts.c:630
Inline: False
```
**Symbols:**

```
ffffffff81003e00-ffffffff81003e20: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:662
Inline: False
```
**Symbols:**

```
ffffffff81003e30-ffffffff81003e6b: rootfs_init_fs_context (STB_LOCAL)
ffffffff81c9491f-ffffffff81c94933: rootfs_init_fs_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:661
Inline: False
```
**Symbols:**

```
ffffffff81001b00-ffffffff81001b4e: rootfs_init_fs_context (STB_LOCAL)
ffffffff81e43a58-ffffffff81e43a6d: rootfs_init_fs_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:661
Inline: False
```
**Symbols:**

```
ffffffff810021d0-ffffffff8100221e: rootfs_init_fs_context (STB_LOCAL)
ffffffff8204ffe2-ffffffff8204fff7: rootfs_init_fs_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:472
Inline: False
```
**Symbols:**

```
ffffffff81001c90-ffffffff81001cde: rootfs_init_fs_context (STB_LOCAL)
ffffffff820ce49b-ffffffff820ce4b0: rootfs_init_fs_context.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In init/do_mounts.c (0)
Location: init/do_mounts.c:506
Inline: False
```
**Symbols:**

```
ffffffff81001ca0-ffffffff81001cee: rootfs_init_fs_context (STB_LOCAL)
ffffffff821a8cab-ffffffff821a8cc0: rootfs_init_fs_context.cold (STB_LOCAL)
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
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffff8000100852b0)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffff8000100852b0-ffff8000100852fc: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c0303a4c)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
c0303a4c-c0303a84: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (c000000000010a30)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
c000000000010a30-c000000000010a98: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffe0000b468a)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffe0000b468a-ffffffe0000b46d0: rootfs_init_fs_context (STB_LOCAL)
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
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002be0)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffff81002be0-ffffffff81002c00: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff810010c0)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffff810010c0-ffffffff810010e0: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002be0)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffff81002be0-ffffffff81002c00: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int rootfs_init_fs_context(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff81002c30)
Location: init/do_mounts.c:638
Inline: False
```
**Symbols:**

```
ffffffff81002c30-ffffffff81002c50: rootfs_init_fs_context (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
