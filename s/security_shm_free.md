# Function: <code>security_shm_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void security_shm_free(struct shmid_kernel *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8133ecf0)
Location: security/security.c:1079
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff8133ecf0-ffffffff8133ed26: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void security_shm_free(struct shmid_kernel *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81374310)
Location: security/security.c:1103
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff81374310-ffffffff81374346: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void security_shm_free(struct shmid_kernel *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8138ac40)
Location: security/security.c:1124
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff8138ac40-ffffffff8138ac76: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void security_shm_free(struct shmid_kernel *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813a0300)
Location: security/security.c:1860
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff813a0300-ffffffff813a0349: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void security_shm_free(struct shmid_kernel *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c5f90)
Location: security/security.c:1831
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff813c5f90-ffffffff813c5fdf: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f5d00)
Location: security/security.c:1228
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff813f5d00-ffffffff813f5d34: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814113b0)
Location: security/security.c:1861
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff814113b0-ffffffff814113f7: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ec20)
Location: security/security.c:1880
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff8143ec20-ffffffff8143ec69: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814585f0)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff814585f0-ffffffff81458637: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ab54f)
Location: security/security.c:2121
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff814ab590-ffffffff814ab5d7: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c8b4f)
Location: security/security.c:2138
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff814c8b90-ffffffff814c8bd7: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cf18f)
Location: security/security.c:2201
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff814cf1d0-ffffffff814cf217: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81527e4f)
Location: security/security.c:2209
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff81527e90-ffffffff81527ed7: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815bce63)
Location: security/security.c:2220
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff815bcee0-ffffffff815bcf2f: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81669163)
Location: security/security.c:2296
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff816691f0-ffffffff8166923f: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a1763)
Location: security/security.c:3840
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff816a17f0-ffffffff816a183f: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816ddfe3)
Location: security/security.c:3869
Inline: True
Inline callers:
  - security/security.c:security_shm_alloc
Direct callers:
  - ipc/shm.c:shm_rcu_free
```
**Symbols:**

```
ffffffff816de070-ffffffff816de0bf: security_shm_free (STB_GLOBAL)
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
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105444b0)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffff8000105444b0-ffff800010544504: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fa3ac)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
c06fa3ac-c06fa404: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c0000000006991f0)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
c0000000006991f0-c00000000069927c: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a0636)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffe0003a0636-ffffffe0003a067e: security_shm_free (STB_GLOBAL)
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
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81450bd0)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff81450bd0-ffffffff81450c17: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81441620)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff81441620-ffffffff81441667: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144cc70)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff8144cc70-ffffffff8144ccb7: security_shm_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void security_shm_free(struct kern_ipc_perm *shp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81464040)
Location: security/security.c:1919
Inline: False
Direct callers:
  - ipc/shm.c:shm_rcu_free
  - security/security.c:security_shm_alloc
```
**Symbols:**

```
ffffffff81464040-ffffffff81464087: security_shm_free (STB_GLOBAL)
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
