# Function: <code>security_node_sid</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81358770)
Location: security/selinux/ss/services.c:2272
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff81358770-ffffffff81358877: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8138e6c0)
Location: security/selinux/ss/services.c:2266
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff8138e6c0-ffffffff8138e7d4: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813a52e0)
Location: security/selinux/ss/services.c:2266
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff813a52e0-ffffffff813a53f4: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813bbdb0)
Location: security/selinux/ss/services.c:2382
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff813bbdb0-ffffffff813bbeb8: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff813e1f20)
Location: security/selinux/ss/services.c:2392
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff813e1f20-ffffffff813e2028: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81412ca0)
Location: security/selinux/ss/services.c:2473
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff81412ca0-ffffffff81412dc3: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8142f1e0)
Location: security/selinux/ss/services.c:2439
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff8142f1e0-ffffffff8142f306: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145cb90)
Location: security/selinux/ss/services.c:2452
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff8145cb90-ffffffff8145ccae: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81476940)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff81476940-ffffffff81476a5e: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814cbf90)
Location: security/selinux/ss/services.c:2502
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff814cbf90-ffffffff814cc0be: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814e93b0)
Location: security/selinux/ss/services.c:2571
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff814e93b0-ffffffff814e94cf: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff814efeb0)
Location: security/selinux/ss/services.c:2626
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid_slow
  - security/selinux/netnode.c:sel_netnode_sid_slow
```
**Symbols:**

```
ffffffff814efeb0-ffffffff814f0015: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2650
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff81cd508d-ffffffff81cd50a1: security_node_sid.cold (STB_LOCAL)
ffffffff8154a400-ffffffff8154a57c: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2652
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff81e87ed9-ffffffff81e87eee: security_node_sid.cold (STB_LOCAL)
ffffffff815e30d0-ffffffff815e3274: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2645
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff82073dc2-ffffffff82073dd7: security_node_sid.cold (STB_LOCAL)
ffffffff81692330-ffffffff816924d4: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2599
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff820f3975-ffffffff820f3989: security_node_sid.cold (STB_LOCAL)
ffffffff816ca880-ffffffff816caa42: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int security_node_sid(u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/ss/services.c (0)
Location: security/selinux/ss/services.c:2609
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff821d0b3b-ffffffff821d0b4f: security_node_sid.cold (STB_LOCAL)
ffffffff81707490-ffffffff81707652: security_node_sid (STB_GLOBAL)
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
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffff800010566538)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffff800010566538-ffff8000105666e0: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c071ab54)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
c071ab54-c071acc0: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (c0000000006c9130)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
c0000000006c9130-c0000000006c9318: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffe0003bc5c8)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffe0003bc5c8-ffffffe0003bc6c4: security_node_sid (STB_GLOBAL)
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
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146ef20)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff8146ef20-ffffffff8146f03e: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8145f940)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff8145f940-ffffffff8145fa5e: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff8146afc0)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff8146afc0-ffffffff8146b0de: security_node_sid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int security_node_sid(struct selinux_state *state, u16 domain, void *addrp, u32 addrlen, u32 *out_sid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/services.c (ffffffff81482760)
Location: security/selinux/ss/services.c:2459
Inline: False
Direct callers:
  - security/selinux/netnode.c:sel_netnode_sid
  - security/selinux/netnode.c:sel_netnode_sid
```
**Symbols:**

```
ffffffff81482760-ffffffff8148288d: security_node_sid (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>domain, addrp, addrlen, out_sid</code> ➡️ <code>state, domain, addrp, addrlen, out_sid</code>
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct selinux_state *state</code>
</li>
<li>
<b>Param reordered. </b>
<code>state, domain, addrp, addrlen, out_sid</code> ➡️ <code>domain, addrp, addrlen, out_sid</code>
</li>
</ul>
</details>
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
