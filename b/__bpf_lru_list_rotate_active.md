# Function: <code>__bpf_lru_list_rotate_active</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811962b0)
Location: kernel/bpf/bpf_lru_list.c:142
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811962b0-ffffffff81196340: __bpf_lru_list_rotate_active.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119d780)
Location: kernel/bpf/bpf_lru_list.c:142
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8119d780-ffffffff8119d80e: __bpf_lru_list_rotate_active.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad340)
Location: kernel/bpf/bpf_lru_list.c:142
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ad340-ffffffff811ad3ce: __bpf_lru_list_rotate_active.isra.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c48c0)
Location: kernel/bpf/bpf_lru_list.c:142
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811c48c0-ffffffff811c494e: __bpf_lru_list_rotate_active.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d64b0)
Location: kernel/bpf/bpf_lru_list.c:142
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811d64b0-ffffffff811d653e: __bpf_lru_list_rotate_active.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eae80)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811eae80-ffffffff811eaf0e: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f75e0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811f75e0-ffffffff811f766e: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b240)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121b240-ffffffff8121b2d6: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e1c0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121e1c0-ffffffff8121e256: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81221cb0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81221cb0-ffffffff81221d46: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81259a30)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81259a30-ffffffff81259b1c: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a2a20)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff812a2a20-ffffffff812a2b25: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81300530)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81300530-ffffffff8130062f: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f090)
Location: kernel/bpf/bpf_lru_list.c:144
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8132f090-ffffffff8132f192: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff813535b0)
Location: kernel/bpf/bpf_lru_list.c:144
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff813535b0-ffffffff813536b2: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027c4d0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffff80001027c4d0-ffff80001027c560: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae080)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c04ae080-c04ae0f8: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000325cc0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c000000000325cc0-c000000000325d94: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_active(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3d5a)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffe0001b3d5a-ffffffe0001b3dd4: __bpf_lru_list_rotate_active (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811efc00)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811efc00-ffffffff811efc8e: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2950)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811e2950-ffffffff811e29de: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ed9d0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811ed9d0-ffffffff811eda5e: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fbea0)
Location: kernel/bpf/bpf_lru_list.c:139
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811fbea0-ffffffff811fbf2e: __bpf_lru_list_rotate_active.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
