# Function: <code>sanitize_global_limit</code>

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
In fs/fuse/inode.c (ffffffff8131b41a)
Location: fs/fuse/inode.c:819
Inline: True
Inline callers:
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff81350234)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff81365b64)
Location: fs/fuse/inode.c:826
Inline: True
Inline callers:
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff8137a204)
Location: fs/fuse/inode.c:819
Inline: True
Inline callers:
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff8139f0a4)
Location: fs/fuse/inode.c:819
Inline: True
Inline callers:
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff8271546d)
Location: fs/fuse/inode.c:822
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828cc8c6)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828e6235)
Location: fs/fuse/inode.c:823
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828eecfb)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void sanitize_global_limit(unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8147d2c6)
Location: fs/fuse/inode.c:839
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
Direct callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
```
**Symbols:**

```
ffffffff8147c260-ffffffff8147c2a5: sanitize_global_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void sanitize_global_limit(unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814984d6)
Location: fs/fuse/inode.c:915
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
Direct callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
```
**Symbols:**

```
ffffffff814971b0-ffffffff814971f5: sanitize_global_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sanitize_global_limit(unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff8149d706)
Location: fs/fuse/inode.c:955
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
Direct callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
```
**Symbols:**

```
ffffffff8149c320-ffffffff8149c365: sanitize_global_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void sanitize_global_limit(unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff814f5156)
Location: fs/fuse/inode.c:1007
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
Direct callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
```
**Symbols:**

```
ffffffff814f3e20-ffffffff814f3e65: sanitize_global_limit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void sanitize_global_limit(unsigned int *limit);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/inode.c (ffffffff815850a0)
Location: fs/fuse/inode.c:1049
Inline: True
Inline callers:
  - fs/fuse/inode.c:set_global_limit
Direct callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
```
**Symbols:**

```
ffffffff815837c0-ffffffff8158380e: sanitize_global_limit (STB_LOCAL)
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
In fs/fuse/inode.c (ffffffff83ecec3a)
Location: fs/fuse/inode.c:1062
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
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
In fs/fuse/inode.c (ffffffff836f3cca)
Location: fs/fuse/inode.c:1062
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
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
In fs/fuse/inode.c (ffffffff83926e9a)
Location: fs/fuse/inode.c:1139
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:set_global_limit
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
In fs/fuse/inode.c (ffff800011468860)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (c1541220)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (c000000001396640)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffe000023b0a)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828d7baf)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828d02cb)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828ea92f)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
In fs/fuse/inode.c (ffffffff828efd45)
Location: fs/fuse/inode.c:825
Inline: True
Inline callers:
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:fuse_init
  - fs/fuse/inode.c:process_init_reply
  - fs/fuse/inode.c:process_init_reply
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
</ul>
