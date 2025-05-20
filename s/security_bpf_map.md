# Function: <code>security_bpf_map</code>

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
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813c7450)
Location: security/security.c:2453
Inline: False
```
**Symbols:**

```
ffffffff813c7450-ffffffff813c74a5: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff813f6ae0)
Location: security/security.c:1766
Inline: False
```
**Symbols:**

```
ffffffff813f6ae0-ffffffff813f6b24: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81412590)
Location: security/security.c:2526
Inline: False
```
**Symbols:**

```
ffffffff81412590-ffffffff814125d4: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8143ff60)
Location: security/security.c:2543
Inline: False
```
**Symbols:**

```
ffffffff8143ff60-ffffffff8143ffad: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814597d0)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffffffff814597d0-ffffffff81459814: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814ac8e0)
Location: security/security.c:2953
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814ac8e0-ffffffff814ac924: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814c9ee0)
Location: security/security.c:2971
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814c9ee0-ffffffff814c9f24: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814d0510)
Location: security/security.c:3034
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__do_sys_bpf
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff814d0510-ffffffff814d0554: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81529240)
Location: security/security.c:3042
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff81529240-ffffffff81529284: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815be880)
Location: security/security.c:3120
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff815be880-ffffffff815be8dd: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8166ab10)
Location: security/security.c:3100
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:__sys_bpf
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff8166ab10-ffffffff8166ab6d: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816a3270)
Location: security/security.c:5512
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff816a3270-ffffffff816a32cd: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816dfcf0)
Location: security/security.c:5653
Inline: False
Direct callers:
  - kernel/bpf/syscall.c:bpf_map_get_fd_by_id
  - kernel/bpf/syscall.c:map_create
```
**Symbols:**

```
ffffffff816dfcf0-ffffffff816dfd4d: security_bpf_map (STB_GLOBAL)
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
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffff8000105459c0)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffff8000105459c0-ffff800010545a20: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c06fb81c)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
c06fb81c-c06fb878: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (c00000000069c0a0)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
c00000000069c0a0-c00000000069c15c: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffe0003a1604)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffffffe0003a1604-ffffffe0003a1648: security_bpf_map (STB_GLOBAL)
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
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81451db0)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffffffff81451db0-ffffffff81451df4: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81442800)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffffffff81442800-ffffffff81442844: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8144de50)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffffffff8144de50-ffffffff8144de94: security_bpf_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_bpf_map(struct bpf_map *map, fmode_t fmode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81465220)
Location: security/security.c:2582
Inline: False
```
**Symbols:**

```
ffffffff81465220-ffffffff81465264: security_bpf_map (STB_GLOBAL)
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
