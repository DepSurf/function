# Function: <code>__bpf_prog_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81171090)
Location: kernel/bpf/core.c:133
Inline: True
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:sk_attach_filter
  - net/core/filter.c:sk_attach_filter
```
**Symbols:**

```
ffffffff81171090-ffffffff811710b1: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117f14b)
Location: kernel/bpf/core.c:133
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8117e9c0-ffffffff8117e9e1: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118afbb)
Location: kernel/bpf/core.c:143
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8118a620-ffffffff8118a641: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118fadd)
Location: kernel/bpf/core.c:146
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8118ed60-ffffffff8118ed81: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119df6a)
Location: kernel/bpf/core.c:142
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8119d1d0-ffffffff8119d1f1: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b2684)
Location: kernel/bpf/core.c:144
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811b1920-ffffffff811b1941: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c11ce)
Location: kernel/bpf/core.c:232
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811c0160-ffffffff811c0181: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d18f8)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811d0af0-ffffffff811d0b29: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dde78)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811dd080-ffffffff811dd0b9: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faf7a)
Location: kernel/bpf/core.c:253
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811f9aa0-ffffffff811f9aec: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f98d8)
Location: kernel/bpf/core.c:247
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811f8ad0-ffffffff811f8b1c: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811fa7ff)
Location: kernel/bpf/core.c:252
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811f98c0-ffffffff811f990f: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122bf1b)
Location: kernel/bpf/core.c:252
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8122af70-ffffffff8122afbf: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126da92)
Location: kernel/bpf/core.c:257
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff8126c930-ffffffff8126c983: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c2ed1)
Location: kernel/bpf/core.c:265
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff812c1a30-ffffffff812c1a83: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e9dc4)
Location: kernel/bpf/core.c:266
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff812e88b0-ffffffff812e8903: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308e4e)
Location: kernel/bpf/core.c:270
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_free_deferred
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - arch/x86/net/bpf_jit_comp.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff81306c20-ffffffff81306c73: __bpf_prog_free (STB_GLOBAL)
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
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025ee18)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffff80001025dbb8-ffff80001025dbfc: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0492394)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
c04912ac-c04912ec: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000303d74)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free
  - arch/powerpc/net/bpf_jit_comp64.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
c000000000302640-c0000000003026a8: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019cf9a)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffe00019c068-ffffffe00019c0ac: __bpf_prog_free (STB_GLOBAL)
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
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d6498)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811d56a0-ffffffff811d56d9: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c9258)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811c8460-ffffffff811c8499: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d4268)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811d3470-ffffffff811d34a9: __bpf_prog_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __bpf_prog_free(struct bpf_prog *fp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e2588)
Location: kernel/bpf/core.c:254
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
  - kernel/bpf/core.c:bpf_prog_realloc
Direct callers:
  - kernel/bpf/core.c:bpf_jit_free
  - net/core/filter.c:__get_filter
  - net/core/filter.c:__get_filter
  - net/core/filter.c:bpf_prog_create_from_user
  - net/core/filter.c:bpf_prog_create_from_user
```
**Symbols:**

```
ffffffff811e1760-ffffffff811e1799: __bpf_prog_free (STB_GLOBAL)
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
