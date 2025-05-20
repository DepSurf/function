# Function: <code>selinux_shm_shmctl</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813463f0)
Location: security/selinux/hooks.c:5409
Inline: True
```
**Symbols:**

```
ffffffff813463b0-ffffffff813463e9: selinux_shm_shmctl.part.30 (STB_LOCAL)
ffffffff813463f0-ffffffff8134643b: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137bb40)
Location: security/selinux/hooks.c:5553
Inline: True
```
**Symbols:**

```
ffffffff8137bb00-ffffffff8137bb39: selinux_shm_shmctl.part.31 (STB_LOCAL)
ffffffff8137bb40-ffffffff8137bb8e: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81391fb0)
Location: security/selinux/hooks.c:5634
Inline: True
```
**Symbols:**

```
ffffffff81391f70-ffffffff81391fa9: selinux_shm_shmctl.part.33 (STB_LOCAL)
ffffffff81391fb0-ffffffff81391ffe: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813a8440)
Location: security/selinux/hooks.c:5552
Inline: True
```
**Symbols:**

```
ffffffff813a83a0-ffffffff813a83d9: selinux_shm_shmctl.part.30 (STB_LOCAL)
ffffffff813a8440-ffffffff813a8486: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct shmid_kernel *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813cdbe0)
Location: security/selinux/hooks.c:5567
Inline: True
```
**Symbols:**

```
ffffffff813cdb40-ffffffff813cdb79: selinux_shm_shmctl.part.31 (STB_LOCAL)
ffffffff813cdbe0-ffffffff813cdc2c: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff813fb230)
Location: security/selinux/hooks.c:6179
Inline: True
```
**Symbols:**

```
ffffffff813fb170-ffffffff813fb1b1: selinux_shm_shmctl.part.41 (STB_LOCAL)
ffffffff813fb230-ffffffff813fb284: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffff81417700)
Location: security/selinux/hooks.c:5842
Inline: True
```
**Symbols:**

```
ffffffff81417620-ffffffff81417661: selinux_shm_shmctl.part.38 (STB_LOCAL)
ffffffff81417700-ffffffff81417762: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814452d0)
Location: security/selinux/hooks.c:6041
Inline: True
```
**Symbols:**

```
ffffffff814452d0-ffffffff8144536d: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8145ee40)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffffffff8145ee40-ffffffff8145eee5: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814af9d0)
Location: security/selinux/hooks.c:6102
Inline: False
```
**Symbols:**

```
ffffffff814af9d0-ffffffff814afa75: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814cd470)
Location: security/selinux/hooks.c:6118
Inline: False
```
**Symbols:**

```
ffffffff814cd470-ffffffff814cd515: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814d3a70)
Location: security/selinux/hooks.c:6282
Inline: False
```
**Symbols:**

```
ffffffff814d3a70-ffffffff814d3b15: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8152c730)
Location: security/selinux/hooks.c:6267
Inline: False
```
**Symbols:**

```
ffffffff8152c730-ffffffff8152c7d5: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff815c2940)
Location: security/selinux/hooks.c:6166
Inline: False
```
**Symbols:**

```
ffffffff815c2940-ffffffff815c2a2d: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8166f180)
Location: security/selinux/hooks.c:6177
Inline: False
```
**Symbols:**

```
ffffffff8166f180-ffffffff8166f26d: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816a7780)
Location: security/selinux/hooks.c:6119
Inline: False
```
**Symbols:**

```
ffffffff816a7780-ffffffff816a785e: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff816e41d0)
Location: security/selinux/hooks.c:6202
Inline: False
```
**Symbols:**

```
ffffffff816e41d0-ffffffff816e42b1: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffff80001054bf48)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffff80001054be08-ffff80001054be5c: selinux_shm_shmctl.part.0 (STB_LOCAL)
ffff80001054bf48-ffff80001054bff8: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (c0702254)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
c0702124-c070218c: selinux_shm_shmctl.part.0 (STB_LOCAL)
c0702254-c07022f0: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (c0000000006a4760)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
c0000000006a4760-c0000000006a4888: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (ffffffe0003a66ce)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffffffe0003a6606-ffffffe0003a664a: selinux_shm_shmctl.part.0 (STB_LOCAL)
ffffffe0003a66ce-ffffffe0003a674a: selinux_shm_shmctl (STB_LOCAL)
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
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81457420)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffffffff81457420-ffffffff814574c5: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81447e50)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffffffff81447e50-ffffffff81447ef5: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814534c0)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffffffff814534c0-ffffffff81453565: selinux_shm_shmctl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int selinux_shm_shmctl(struct kern_ipc_perm *shp, int cmd);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8146b040)
Location: security/selinux/hooks.c:6099
Inline: True
```
**Symbols:**

```
ffffffff8146b040-ffffffff8146b0e5: selinux_shm_shmctl (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct shmid_kernel *shp</code> ➡️ <code>struct kern_ipc_perm *shp</code>
</li>
</ul>
</details>
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
