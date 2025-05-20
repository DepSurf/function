# Function: <code>selinux_inode_getsecid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(const struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81341870)
Location: security/selinux/hooks.c:3208
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_getpeersec_dgram
```
**Symbols:**

```
ffffffff81341870-ffffffff81341884: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81376f10)
Location: security/selinux/hooks.c:3290
Inline: False
```
**Symbols:**

```
ffffffff81376f10-ffffffff81376f24: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138ff45)
Location: security/selinux/hooks.c:3327
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff8138d840-ffffffff8138d854: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a64f5)
Location: security/selinux/hooks.c:3309
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff813a3600-ffffffff813a361c: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cc135)
Location: security/selinux/hooks.c:3324
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff813c9400-ffffffff813c941c: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813faa6d)
Location: security/selinux/hooks.c:3485
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff813f8b80-ffffffff813f8b94: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81416ed4)
Location: security/selinux/hooks.c:3233
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff814146a0-ffffffff814146c3: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8144494a)
Location: security/selinux/hooks.c:3360
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff81442250-ffffffff81442273: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145e4ba)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff8145bcc0-ffffffff8145bce3: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b163a)
Location: security/selinux/hooks.c:3405
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff814aeef0-ffffffff814aef13: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814ce85a)
Location: security/selinux/hooks.c:3425
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff814cc990-ffffffff814cc9b3: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d4fba)
Location: security/selinux/hooks.c:3584
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff814d2fc0-ffffffff814d2fe3: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152dc5a)
Location: security/selinux/hooks.c:3569
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff8152bc80-ffffffff8152bca3: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c468a)
Location: security/selinux/hooks.c:3459
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff815c19e0-ffffffff815c1a0f: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8167116a)
Location: security/selinux/hooks.c:3477
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff8166e060-ffffffff8166e08f: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a982a)
Location: security/selinux/hooks.c:3469
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff816a6730-ffffffff816a675f: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffff80001054b4e8)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffff8000105486d0-ffff800010548714: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c07017d8)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
c06fe188-c06fe1c0: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a3cb4)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
c00000000069f730-c00000000069f764: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a5fba)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffe0003a391c-ffffffe0003a3956: selinux_inode_getsecid (STB_LOCAL)
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
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81456a9a)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff814542a0-ffffffff814542c3: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814474da)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff81444ce0-ffffffff81444d03: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81452b3a)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff81450340-ffffffff81450363: selinux_inode_getsecid (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void selinux_inode_getsecid(struct inode *inode, u32 *secid);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814698ca)
Location: security/selinux/hooks.c:3418
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_inode_copy_up
```
**Symbols:**

```
ffffffff814677e0-ffffffff81467803: selinux_inode_getsecid (STB_LOCAL)
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
<b>Param type changed. </b>
<code>const struct inode *inode</code> ➡️ <code>struct inode *inode</code>
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
