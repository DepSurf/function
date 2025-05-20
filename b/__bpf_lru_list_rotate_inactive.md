# Function: <code>__bpf_lru_list_rotate_inactive</code>

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
In kernel/bpf/bpf_lru_list.c (ffffffff81196340)
Location: kernel/bpf/bpf_lru_list.c:169
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff81196340-ffffffff811963e1: __bpf_lru_list_rotate_inactive.isra.6 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff8119d810)
Location: kernel/bpf/bpf_lru_list.c:169
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff8119d810-ffffffff8119d8b1: __bpf_lru_list_rotate_inactive.isra.6 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811ad3d0)
Location: kernel/bpf/bpf_lru_list.c:169
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811ad3d0-ffffffff811ad471: __bpf_lru_list_rotate_inactive.isra.6 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811c4950)
Location: kernel/bpf/bpf_lru_list.c:169
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811c4950-ffffffff811c49f1: __bpf_lru_list_rotate_inactive.isra.7 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811d6540)
Location: kernel/bpf/bpf_lru_list.c:169
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffffffff811d6540-ffffffff811d65e1: __bpf_lru_list_rotate_inactive.isra.8 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eaf10)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811eaf10-ffffffff811eafb7: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811f7670)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811f7670-ffffffff811f7717: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b2e0)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121b2e0-ffffffff8121b38f: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e260)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_percpu_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8121e260-ffffffff8121e30f: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81221d50)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81221d50-ffffffff81221dff: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81259830)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81259830-ffffffff812598df: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a27e0)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff812a27e0-ffffffff812a28a4: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff813002c0)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff813002c0-ffffffff81300384: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132ee20)
Location: kernel/bpf/bpf_lru_list.c:171
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff8132ee20-ffffffff8132eee9: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81353340)
Location: kernel/bpf/bpf_lru_list.c:171
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_list_pop_free_to_local
```
**Symbols:**

```
ffffffff81353340-ffffffff81353409: __bpf_lru_list_rotate_inactive (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffff80001027c560)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
**Symbols:**

```
ffff80001027c560-ffff80001027c630: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae0f8)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c04ae0f8-c04ae1a8: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c000000000325da0)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
c000000000325da0-c000000000325ec0: __bpf_lru_list_rotate_inactive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __bpf_lru_list_rotate_inactive(struct bpf_lru *lru, struct bpf_lru_list *l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffe0001b3dd4)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffe0001b3dd4-ffffffe0001b3e76: __bpf_lru_list_rotate_inactive (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811efc90)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811efc90-ffffffff811efd37: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811e29e0)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811e29e0-ffffffff811e2a87: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811eda60)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811eda60-ffffffff811edb07: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
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
In kernel/bpf/bpf_lru_list.c (ffffffff811fbf30)
Location: kernel/bpf/bpf_lru_list.c:166
Inline: True
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff811fbf30-ffffffff811fbfd7: __bpf_lru_list_rotate_inactive.isra.0 (STB_LOCAL)
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
