# Function: <code>sel_netif_sid_slow</code>

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
In security/selinux/netif.c (ffffffff8134cee4)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff81382e9b)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff8139991b)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff813afd2b)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff813d5ddb)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff814063e7)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff81421f39)
Location: security/selinux/netif.c:136
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff8144fb38)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff814699a8)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:133
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff814bdb00-ffffffff814bdcab: sel_netif_sid_slow (STB_LOCAL)
ffffffff814bdd9e-ffffffff814bddf7: sel_netif_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:133
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff814db560-ffffffff814db70b: sel_netif_sid_slow (STB_LOCAL)
ffffffff81bf05dd-ffffffff81bf0636: sel_netif_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:132
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff814e1ee0-ffffffff814e208b: sel_netif_sid_slow (STB_LOCAL)
ffffffff81be2727-ffffffff81be2780: sel_netif_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:132
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff8153aee0-ffffffff8153b08b: sel_netif_sid_slow (STB_LOCAL)
ffffffff81cd4190-ffffffff81cd41e9: sel_netif_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/netif.c (0)
Location: security/selinux/netif.c:132
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff815d2650-ffffffff815d27f8: sel_netif_sid_slow (STB_LOCAL)
ffffffff81e8715a-ffffffff81e871b3: sel_netif_sid_slow.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff81680560)
Location: security/selinux/netif.c:132
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff81680560-ffffffff8168075a: sel_netif_sid_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff816b8630)
Location: security/selinux/netif.c:132
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff816b8630-ffffffff816b8823: sel_netif_sid_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sel_netif_sid_slow(struct net *ns, int ifindex, u32 *sid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/netif.c (ffffffff816f5060)
Location: security/selinux/netif.c:132
Inline: False
Direct callers:
  - security/selinux/netif.c:sel_netif_sid
```
**Symbols:**

```
ffffffff816f5060-ffffffff816f5280: sel_netif_sid_slow (STB_LOCAL)
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
In security/selinux/netif.c (ffff800010557fd4)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (c070ce20)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (c0000000006b603c)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffe0003af822)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff81461f88)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff814529b8)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff8145e028)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
In security/selinux/netif.c (ffffffff814757df)
Location: security/selinux/netif.c:133
Inline: True
Inline callers:
  - security/selinux/netif.c:sel_netif_sid
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
