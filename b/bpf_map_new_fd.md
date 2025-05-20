# Function: <code>bpf_map_new_fd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811733f0)
Location: kernel/bpf/syscall.c:120
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811733f0-ffffffff81173416: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81181ace)
Location: kernel/bpf/syscall.c:162
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81181370-ffffffff81181396: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118dcf9)
Location: kernel/bpf/syscall.c:203
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff8118cf80-ffffffff8118cfa6: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811933d9)
Location: kernel/bpf/syscall.c:257
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81191e00-ffffffff81191e26: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119f4e0)
Location: kernel/bpf/syscall.c:327
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/syscall.c:SyS_bpf
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff8119f4e0-ffffffff8119f52c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b5110)
Location: kernel/bpf/syscall.c:376
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811b5110-ffffffff811b515c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c3520)
Location: kernel/bpf/syscall.c:404
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811c3520-ffffffff811c356c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4280)
Location: kernel/bpf/syscall.c:436
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811d4280-ffffffff811d42cc: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e0980)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811e0980-ffffffff811e09cc: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fea85)
Location: kernel/bpf/syscall.c:678
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811feb00-ffffffff811feb4c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fdda5)
Location: kernel/bpf/syscall.c:685
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811fde20-ffffffff811fde6c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81202237)
Location: kernel/bpf/syscall.c:686
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811fe8b0-ffffffff811fe8fc: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81233ee0)
Location: kernel/bpf/syscall.c:702
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812304f0-ffffffff8123053c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81277379)
Location: kernel/bpf/syscall.c:823
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81273430-ffffffff81273488: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812cd4a1)
Location: kernel/bpf/syscall.c:922
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812c9b60-ffffffff812c9bb8: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812f2607)
Location: kernel/bpf/syscall.c:921
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff812f1360-ffffffff812f13b8: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff813114a7)
Location: kernel/bpf/syscall.c:951
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:map_create
Direct callers:
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff81310190-ffffffff813101e8: bpf_map_new_fd (STB_GLOBAL)
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
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff800010262f70)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffff800010262f70-ffff800010262fd4: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0495b70)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
c0495b70-c0495bc8: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0000000003080f0)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
c0000000003080f0-c00000000030817c: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019f8fa)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffe00019f8fa-ffffffe00019f95e: bpf_map_new_fd (STB_GLOBAL)
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
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d8fa0)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811d8fa0-ffffffff811d8fec: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811cbd60)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811cbd60-ffffffff811cbdac: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6d70)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811d6d70-ffffffff811d6dbc: bpf_map_new_fd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bpf_map_new_fd(struct bpf_map *map, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e50e0)
Location: kernel/bpf/syscall.c:439
Inline: True
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/inode.c:bpf_obj_get_user
```
**Symbols:**

```
ffffffff811e50e0-ffffffff811e512c: bpf_map_new_fd (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int flags</code>
</li>
</ul>
</details>
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
