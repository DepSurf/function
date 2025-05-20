# Function: <code>xfrm_init_tempstate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817bae8c)
Location: net/xfrm/xfrm_state.c:633
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81827d97)
Location: net/xfrm/xfrm_state.c:634
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff818597ee)
Location: net/xfrm/xfrm_state.c:643
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff8187d4fa)
Location: net/xfrm/xfrm_state.c:789
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff818fe366)
Location: net/xfrm/xfrm_state.c:798
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff81954ea4)
Location: net/xfrm/xfrm_state.c:799
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff819898c7)
Location: net/xfrm/xfrm_state.c:812
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff819f3630)
Location: net/xfrm/xfrm_state.c:887
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff81a2a500)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b177d0)
Location: net/xfrm/xfrm_state.c:892
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81b177d0-ffffffff81b17ae8: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b258a0)
Location: net/xfrm/xfrm_state.c:892
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81b258a0-ffffffff81b25bb8: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b136b0)
Location: net/xfrm/xfrm_state.c:891
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81b136b0-ffffffff81b13a08: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd77f0)
Location: net/xfrm/xfrm_state.c:915
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81bd77f0-ffffffff81bd7b63: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6e330)
Location: net/xfrm/xfrm_state.c:916
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81d6e330-ffffffff81d6e6c4: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f39fa0)
Location: net/xfrm/xfrm_state.c:939
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81f39fa0-ffffffff81f3a35d: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f999c0)
Location: net/xfrm/xfrm_state.c:939
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81f999c0-ffffffff81f99d74: xfrm_init_tempstate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82066d20)
Location: net/xfrm/xfrm_state.c:939
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff82066d20-ffffffff820670d4: xfrm_init_tempstate (STB_LOCAL)
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
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffff800010ce3978)
Location: net/xfrm/xfrm_state.c:889
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffff800010ce3978-ffff800010ce3cec: xfrm_init_tempstate (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (c0df0ec0)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (c000000000e0c45c)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void xfrm_init_tempstate(struct xfrm_state *x, const struct flowi *fl, const struct xfrm_tmpl *tmpl, const xfrm_address_t *daddr, const xfrm_address_t *saddr, short unsigned int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffe000832af8)
Location: net/xfrm/xfrm_state.c:889
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffe000832af8-ffffffe000832ef0: xfrm_init_tempstate (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff819c9b90)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff81986980)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff81a34610)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
In net/xfrm/xfrm_state.c (ffffffff81a40034)
Location: net/xfrm/xfrm_state.c:889
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
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
