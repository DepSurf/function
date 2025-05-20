# Function: <code>put_mnt_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812301f0)
Location: fs/namespace.c:3150
Inline: True
Direct callers:
  - kernel/nsproxy.c:create_new_namespaces
  - kernel/nsproxy.c:free_nsproxy
  - fs/namespace.c:mount_subtree
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812301f0-ffffffff8123021b: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81258880)
Location: fs/namespace.c:3137
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff81258880-ffffffff812588ab: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8126bd30)
Location: fs/namespace.c:3281
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff8126bd30-ffffffff8126bd5b: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81279520)
Location: fs/namespace.c:3217
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff81279520-ffffffff8127954c: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8129bf50)
Location: fs/namespace.c:3290
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff8129bf50-ffffffff8129bf7a: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812c2480)
Location: fs/namespace.c:3327
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812c2480-ffffffff812c24aa: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812d7720)
Location: fs/namespace.c:3299
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812d7720-ffffffff812d774a: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f5b80)
Location: fs/namespace.c:3756
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812f5b80-ffffffff812f5bad: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81307700)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff81307700-ffffffff8130772d: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81340bb0)
Location: fs/namespace.c:3842
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff81340bb0-ffffffff81340c1b: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134cc40)
Location: fs/namespace.c:3864
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff8134cc40-ffffffff8134ccd2: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81353820)
Location: fs/namespace.c:4270
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff81353820-ffffffff813538b2: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff813a1c70)
Location: fs/namespace.c:4348
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff813a1c70-ffffffff813a1d02: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814256d0)
Location: fs/namespace.c:4441
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff814256d0-ffffffff8142577a: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814b1e80)
Location: fs/namespace.c:4550
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff814b1e80-ffffffff814b1f2a: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e6ed0)
Location: fs/namespace.c:4742
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff814e6ed0-ffffffff814e6f7a: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8151ad70)
Location: fs/namespace.c:5197
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff8151ad70-ffffffff8151ae1a: put_mnt_ns (STB_GLOBAL)
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
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffff8000103bab48)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffff8000103bab48-ffff8000103baba8: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c05988d4)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
c05988d4-c059892c: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (c0000000004b8410)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
c0000000004b8410-c0000000004b847c: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/namespace.c (ffffffe00027ac92)
Location: fs/namespace.c:3789
Inline: True
Inline callers:
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffe00027aac0-ffffffe00027aaf8: put_mnt_ns.part.0 (STB_LOCAL)
ffffffe00027cf6e-ffffffe00027cfb0: put_mnt_ns (STB_GLOBAL)
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
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ffce0)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812ffce0-ffffffff812ffd0d: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f0900)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812f0900-ffffffff812f092d: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fdad0)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff812fdad0-ffffffff812fdafd: put_mnt_ns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void put_mnt_ns(struct mnt_namespace *ns);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130ee10)
Location: fs/namespace.c:3789
Inline: True
Direct callers:
  - kernel/nsproxy.c:free_nsproxy
  - kernel/nsproxy.c:create_new_namespaces
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_install
  - fs/namespace.c:mntns_put
  - fs/namespace.c:mount_subtree
  - fs/proc_namespace.c:mounts_release
  - fs/proc_namespace.c:mounts_open_common
```
**Symbols:**

```
ffffffff8130ee10-ffffffff8130ee3d: put_mnt_ns (STB_GLOBAL)
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
