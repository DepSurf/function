# Function: <code>prandom_u32_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff813f87f0)
Location: lib/random32.c:59
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:__prandom_timer
```
**Symbols:**

```
ffffffff813f87f0-ffffffff813f887b: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8143f680)
Location: lib/random32.c:59
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff8143f680-ffffffff8143f6ff: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8145c780)
Location: lib/random32.c:59
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff8145c780-ffffffff8145c7ff: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814619b0)
Location: lib/random32.c:59
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff814619b0-ffffffff81461a2f: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8148d8b0)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff8148d8b0-ffffffff8148d92f: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814c2630)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff814c2630-ffffffff814c26aa: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff814d6ce0)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff814d6ce0-ffffffff814d6d5a: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81502b10)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81502b10-ffffffff81502b8a: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81520ab0)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81520ab0-ffffffff81520b2a: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81583f1a)
Location: lib/random32.c:60
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81583c10-ffffffff81583c87: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff815a112a)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff815a0a90-ffffffff815a0b07: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff815a7fda)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff815a7920-ffffffff815a7999: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81610f9a)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81610860-ffffffff816108d9: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff816dcf5a)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff816dcd50-ffffffff816dcdd8: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff817ccd91)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff817ccb60-ffffffff817ccbe8: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8180b1a1)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff8180af70-ffffffff8180aff8: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81851981)
Location: lib/random32.c:52
Inline: True
Inline callers:
  - lib/random32.c:prandom_bytes_state
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_seed_full_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81851750-ffffffff818517d8: prandom_u32_state (STB_GLOBAL)
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
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffff80001062a010)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_u32
```
**Symbols:**

```
ffff80001062a010-ffff80001062a074: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (c07d12ec)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
c07d12ec-c07d1378: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (c0000000007cbe40)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
c0000000007cbe40-c0000000007cbebc: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffe00045aaaa)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_u32
```
**Symbols:**

```
ffffffe00045aaaa-ffffffe00045ab36: prandom_u32_state (STB_GLOBAL)
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
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81519090)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81519090-ffffffff8151910a: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81509390)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81509390-ffffffff8150940a: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff81515120)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:__prandom_timer
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
```
**Symbols:**

```
ffffffff81515120-ffffffff8151519a: prandom_u32_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u32 prandom_u32_state(struct rnd_state *state);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/random32.c (ffffffff8152e890)
Location: lib/random32.c:60
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_user_rnd_u32
  - mm/slab_common.c:cache_random_seq_create
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_warmup
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_bytes_state
  - lib/random32.c:prandom_u32
```
**Symbols:**

```
ffffffff8152e890-ffffffff8152e90a: prandom_u32_state (STB_GLOBAL)
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
