# Function: <code>__nf_hook_entries_try_shrink</code>

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
void *__nf_hook_entries_try_shrink(struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8188bd70)
Location: net/netfilter/core.c:196
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_unregister_net_hooks
  - net/netfilter/core.c:nf_unregister_net_hook
```
**Symbols:**

```
ffffffff8188bd70-ffffffff8188be8b: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818df9d0)
Location: net/netfilter/core.c:221
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff818df9d0-ffffffff818dfae3: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8190c560)
Location: net/netfilter/core.c:221
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff8190c560-ffffffff8190c673: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff8196e160)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff8196e160-ffffffff8196e26b: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819a4ba0)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff819a4ba0-ffffffff819a4cab: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a8da90)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81a8da90-ffffffff81a8dbc4: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a97a60)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81a97a60-ffffffff81a97b94: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81a82db0)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81a82db0-ffffffff81a82ee4: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81b3ca00)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81b3ca00-ffffffff81b3cb71: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81cc9460)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81cc9460-ffffffff81cc962b: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81e89030)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81e89030-ffffffff81e891fb: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81ee7020)
Location: net/netfilter/core.c:234
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81ee7020-ffffffff81ee71eb: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81faae30)
Location: net/netfilter/core.c:234
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81faae30-ffffffff81faaffb: __nf_hook_entries_try_shrink (STB_LOCAL)
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
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffff800010c53fe0)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffff800010c53fe0-ffff800010c54120: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c0d63d34)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
c0d63d34-c0d63e94: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (c000000000d53b70)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
c000000000d53b70-c000000000d53d38: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffe0007be782)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffe0007be782-ffffffe0007be888: __nf_hook_entries_try_shrink (STB_LOCAL)
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
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81944a10)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81944a10-ffffffff81944b1b: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff818fe500)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff818fe500-ffffffff818fe60b: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff81995ba0)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff81995ba0-ffffffff81995cab: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__nf_hook_entries_try_shrink(struct nf_hook_entries *old, struct nf_hook_entries **pp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netfilter/core.c (ffffffff819b8780)
Location: net/netfilter/core.c:222
Inline: False
Direct callers:
  - net/netfilter/core.c:nf_hook_entries_delete_raw
  - net/netfilter/core.c:__nf_unregister_net_hook
```
**Symbols:**

```
ffffffff819b8780-ffffffff819b888b: __nf_hook_entries_try_shrink (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct nf_hook_entries *old</code>
</li>
<li>
<b>Param reordered. </b>
<code>pp</code> ➡️ <code>old, pp</code>
</li>
</ul>
</details>
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
