# Function: <code>bpf_map_put_uref</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811729a0)
Location: kernel/bpf/syscall.c:85
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811729a0-ffffffff811729bf: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811807c0)
Location: kernel/bpf/syscall.c:100
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811807c0-ffffffff811807de: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8118c630)
Location: kernel/bpf/syscall.c:128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff8118c630-ffffffff8118c64e: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81191610)
Location: kernel/bpf/syscall.c:170
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff81191610-ffffffff8119162e: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e560)
Location: kernel/bpf/syscall.c:220
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff8119e560-ffffffff8119e57e: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b2d30)
Location: kernel/bpf/syscall.c:265
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811b2d30-ffffffff811b2d55: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1940)
Location: kernel/bpf/syscall.c:293
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811c1940-ffffffff811c1965: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d2070)
Location: kernel/bpf/syscall.c:311
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d2070-ffffffff811d2096: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de610)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811de610-ffffffff811de636: bpf_map_put_uref (STB_LOCAL)
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
In kernel/bpf/syscall.c (ffffffff811fe955)
Location: kernel/bpf/syscall.c:468
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
In kernel/bpf/syscall.c (ffffffff811fdc75)
Location: kernel/bpf/syscall.c:462
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
In kernel/bpf/syscall.c (ffffffff811fe835)
Location: kernel/bpf/syscall.c:463
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
In kernel/bpf/syscall.c (ffffffff81230475)
Location: kernel/bpf/syscall.c:482
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
In kernel/bpf/syscall.c (ffffffff812733b5)
Location: kernel/bpf/syscall.c:603
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
In kernel/bpf/syscall.c (ffffffff812c9ac5)
Location: kernel/bpf/syscall.c:700
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eb4c0)
Location: kernel/bpf/syscall.c:711
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff812eb4c0-ffffffff812eb4f7: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309a10)
Location: kernel/bpf/syscall.c:717
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff81309a10-ffffffff81309a47: bpf_map_put_uref (STB_LOCAL)
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
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025fe40)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffff80001025fe40-ffff80001025fea8: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0492d04)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
c0492d04-c0492d5c: bpf_map_put_uref (STB_LOCAL)
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
In kernel/bpf/syscall.c (c000000000308008)
Location: kernel/bpf/syscall.c:314
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
In kernel/bpf/syscall.c (ffffffe00019f858)
Location: kernel/bpf/syscall.c:314
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_map_put_with_uref
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
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6c30)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d6c30-ffffffff811d6c56: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c99f0)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811c99f0-ffffffff811c9a16: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4a00)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811d4a00-ffffffff811d4a26: bpf_map_put_uref (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_map_put_uref(struct bpf_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e2d30)
Location: kernel/bpf/syscall.c:314
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
  - kernel/bpf/syscall.c:bpf_map_release
```
**Symbols:**

```
ffffffff811e2d30-ffffffff811e2d56: bpf_map_put_uref (STB_LOCAL)
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
