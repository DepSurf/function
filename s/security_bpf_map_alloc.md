# Function: <code>security_bpf_map_alloc</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c7500)
Location: security/security.c:2461
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:SyS_bpf
```
**Symbols:**

```
ffffffff813c7500-ffffffff813c7549: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6b70)
Location: security/security.c:1774
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff813f6b70-ffffffff813f6baa: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81412620)
Location: security/security.c:2534
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
```
**Symbols:**

```
ffffffff81412620-ffffffff8141265a: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81440000)
Location: security/security.c:2551
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff81440000-ffffffff81440041: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81459860)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff81459860-ffffffff8145989a: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac970)
Location: security/security.c:2961
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814ac970-ffffffff814ac9aa: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9f70)
Location: security/security.c:2979
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814c9f70-ffffffff814c9faa: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d05a0)
Location: security/security.c:3042
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814d05a0-ffffffff814d05da: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815292d0)
Location: security/security.c:3050
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff815292d0-ffffffff8152930a: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be930)
Location: security/security.c:3128
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff815be930-ffffffff815be97d: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166abe0)
Location: security/security.c:3108
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff8166abe0-ffffffff8166ac2d: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a3340)
Location: security/security.c:5539
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff816a3340-ffffffff816a338d: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dfdc0)
Location: security/security.c:5680
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff816dfdc0-ffffffff816dfe0d: security_bpf_map_alloc (STB_GLOBAL)
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
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff800010545a70)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffff800010545a70-ffff800010545ac0: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb8cc)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
c06fb8cc-c06fb920: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069c210)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
c00000000069c210-c00000000069c2b8: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a1684)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffe0003a1684-ffffffe0003a16c0: security_bpf_map_alloc (STB_GLOBAL)
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
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451e40)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff81451e40-ffffffff81451e7a: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442890)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff81442890-ffffffff814428ca: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144dee0)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff8144dee0-ffffffff8144df1a: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_bpf_map_alloc(struct bpf_map *map);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814652b0)
Location: security/security.c:2590
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814652b0-ffffffff814652ea: security_bpf_map_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
