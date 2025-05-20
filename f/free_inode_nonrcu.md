# Function: <code>free_inode_nonrcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81226c30)
Location: fs/inode.c:216
Inline: False
```
**Symbols:**

```
ffffffff81226c30-ffffffff81226c4a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8124f350)
Location: fs/inode.c:223
Inline: False
```
**Symbols:**

```
ffffffff8124f350-ffffffff8124f36a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81262380)
Location: fs/inode.c:225
Inline: False
```
**Symbols:**

```
ffffffff81262380-ffffffff8126239a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8126fc20)
Location: fs/inode.c:226
Inline: False
```
**Symbols:**

```
ffffffff8126fc20-ffffffff8126fc3a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81292540)
Location: fs/inode.c:226
Inline: False
```
**Symbols:**

```
ffffffff81292540-ffffffff8129255a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812b8410)
Location: fs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff812b8410-ffffffff812b842a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812cd560)
Location: fs/inode.c:228
Inline: False
```
**Symbols:**

```
ffffffff812cd560-ffffffff812cd57a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812ea1e3)
Location: fs/inode.c:206
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff812ea1a0-ffffffff812ea1ba: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812fbc83)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff812fbc40-ffffffff812fbc5a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813358c1)
Location: fs/inode.c:211
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff813349e0-ffffffff813349fa: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81341241)
Location: fs/inode.c:212
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff81340350-ffffffff8134036a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813477b1)
Location: fs/inode.c:212
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff81346880-ffffffff8134689a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff813950a1)
Location: fs/inode.c:216
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff813942b0-ffffffff813942ca: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81417e1f)
Location: fs/inode.c:240
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff81415fd0-ffffffff81415ff2: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814a35df)
Location: fs/inode.c:238
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff814a1450-ffffffff814a1472: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff814d874f)
Location: fs/inode.c:238
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff814d6760-ffffffff814d6782: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff8150afdf)
Location: fs/inode.c:239
Inline: True
Inline callers:
  - fs/inode.c:alloc_inode
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff81508b50-ffffffff81508b72: free_inode_nonrcu (STB_GLOBAL)
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
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffff8000103ab934)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffff8000103ab8c8-ffff8000103ab8fc: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c058c51c)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
c058c4c0-c058c4ec: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (c0000000004a64e0)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
c0000000004a6450-c0000000004a6490: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffe000270c96)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffe000270c3a-ffffffe000270c6c: free_inode_nonrcu (STB_GLOBAL)
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
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f4263)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff812f4220-ffffffff812f423a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812e4e93)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff812e4e50-ffffffff812e4e6a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff812f2073)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff812f2030-ffffffff812f204a: free_inode_nonrcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void free_inode_nonrcu(struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/inode.c (ffffffff81303643)
Location: fs/inode.c:210
Inline: True
Inline callers:
  - fs/inode.c:i_callback
Direct callers:
  - kernel/bpf/inode.c:bpf_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/configfs/mount.c:configfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - fs/debugfs/inode.c:debugfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/inode.c:securityfs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
  - security/apparmor/apparmorfs.c:aafs_free_inode
```
**Symbols:**

```
ffffffff81303600-ffffffff8130361a: free_inode_nonrcu (STB_GLOBAL)
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
