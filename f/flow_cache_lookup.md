# Function: <code>flow_cache_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct flow_cache_object *flow_cache_lookup(struct net *net, const struct flowi *key, u16 family, u8 dir, flow_resolve_t resolver, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff81734750)
Location: net/core/flow.c:192
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
```
**Symbols:**

```
ffffffff81734750-ffffffff81734b6c: flow_cache_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct flow_cache_object *flow_cache_lookup(struct net *net, const struct flowi *key, u16 family, u8 dir, flow_resolve_t resolver, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817a0840)
Location: net/core/flow.c:196
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff817a0840-ffffffff817a0c88: flow_cache_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct flow_cache_object *flow_cache_lookup(struct net *net, const struct flowi *key, u16 family, u8 dir, flow_resolve_t resolver, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817cf480)
Location: net/core/flow.c:195
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff817cf480-ffffffff817cf8bf: flow_cache_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct flow_cache_object *flow_cache_lookup(struct net *net, const struct flowi *key, u16 family, u8 dir, flow_resolve_t resolver, void *ctx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow.c (ffffffff817ee7d0)
Location: net/core/flow.c:197
Inline: False
Direct callers:
  - net/xfrm/xfrm_policy.c:__xfrm_policy_check
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff817ee7d0-ffffffff817eec86: flow_cache_lookup (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
