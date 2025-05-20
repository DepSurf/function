# Function: <code>bpf_lru_list_pop_free_to_local</code>

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
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811967b1)
Location: kernel/bpf/bpf_lru_list.c:322
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8119da74)
Location: kernel/bpf/bpf_lru_list.c:321
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811ad6b7)
Location: kernel/bpf/bpf_lru_list.c:321
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811c4ce1)
Location: kernel/bpf/bpf_lru_list.c:321
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811d68d1)
Location: kernel/bpf/bpf_lru_list.c:321
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eb218)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811f7978)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121b790)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff8121b790-ffffffff8121b8b0: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8121e710)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff8121e710-ffffffff8121e830: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81221f50)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff81221f50-ffffffff8122212e: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81259b20)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff81259b20-ffffffff81259d3e: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff812a2b30)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff812a2b30-ffffffff812a2d7a: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff81300640)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff81300640-ffffffff8130088a: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff8132f1b0)
Location: kernel/bpf/bpf_lru_list.c:323
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff8132f1b0-ffffffff8132f3f0: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bpf_lru_list_pop_free_to_local(struct bpf_lru *lru, struct bpf_lru_locallist *loc_l);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff813536d0)
Location: kernel/bpf/bpf_lru_list.c:323
Inline: False
Direct callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
**Symbols:**

```
ffffffff813536d0-ffffffff81353910: bpf_lru_list_pop_free_to_local (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffff80001027cc44)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (c04ae470)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (c000000000326320)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
In kernel/bpf/bpf_lru_list.c (ffffffe0001b40de)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811eff98)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811e2ce8)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811edd68)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/bpf_lru_list.c (ffffffff811fc238)
Location: kernel/bpf/bpf_lru_list.c:318
Inline: True
Inline callers:
  - kernel/bpf/bpf_lru_list.c:bpf_common_lru_pop_free
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
