# Function: <code>bpf_cgroup_storage_unlink</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811d8860)
Location: kernel/bpf/local_storage.c:561
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_put
  - kernel/bpf/cgroup.c:cgroup_bpf_put
```
**Symbols:**

```
ffffffff811d8860-ffffffff811d88d2: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811ed350)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811ed350-ffffffff811ed3c0: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f9aa0)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811f9aa0-ffffffff811f9b10: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121d910)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff8121d910-ffffffff8121d980: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8121fe0c)
Location: kernel/bpf/local_storage.c:582
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff81220710-ffffffff812207a1: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8122389c)
Location: kernel/bpf/local_storage.c:583
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff812241a0-ffffffff81224231: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8125b6cc)
Location: kernel/bpf/local_storage.c:589
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff8125c0e0-ffffffff8125c171: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff812a50cc)
Location: kernel/bpf/local_storage.c:589
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff812a5d30-ffffffff812a5ddd: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81302eac)
Location: kernel/bpf/local_storage.c:588
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff81303dc0-ffffffff81303e6d: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff8133194d)
Location: kernel/bpf/local_storage.c:595
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff81332740-ffffffff813327ed: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff81355eed)
Location: kernel/bpf/local_storage.c:595
Inline: True
Inline callers:
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
  - kernel/bpf/local_storage.c:cgroup_storage_map_free
Direct callers:
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff81356d10-ffffffff81356dbd: bpf_cgroup_storage_unlink (STB_GLOBAL)
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffff80001027f4e0)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffff80001027f4e0-ffff80001027f5b8: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c04b0868)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
c04b0868-c04b08c8: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (c0000000003296d0)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
c0000000003296d0-c00000000032978c: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffe0001b611c)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffe0001b611c-ffffffe0001b6186: bpf_cgroup_storage_unlink (STB_GLOBAL)
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
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811f20c0)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811f20c0-ffffffff811f2130: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811e4e10)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811e4e10-ffffffff811e4e80: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811efe90)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811efe90-ffffffff811eff00: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bpf_cgroup_storage_unlink(struct bpf_cgroup_storage *storage);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/local_storage.c (ffffffff811fe3a0)
Location: kernel/bpf/local_storage.c:582
Inline: False
Direct callers:
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_detach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:__cgroup_bpf_attach
  - kernel/bpf/cgroup.c:cgroup_bpf_release
  - kernel/bpf/cgroup.c:cgroup_bpf_release
```
**Symbols:**

```
ffffffff811fe3a0-ffffffff811fe410: bpf_cgroup_storage_unlink (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
