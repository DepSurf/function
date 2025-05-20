# Function: <code>vif_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff817a7ca0)
Location: net/ipv4/ipmr.c:712
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff817a7ca0-ffffffff817a82a2: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818905cf)
Location: net/ipv4/ipmr.c:728
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff818905cf-ffffffff81890b5a: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818c4be9)
Location: net/ipv4/ipmr.c:733
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff818c4be9-ffffffff818c5174: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81868de0)
Location: net/ipv4/ipmr.c:753
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81868de0-ffffffff818693b5: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff818e94b0)
Location: net/ipv4/ipmr.c:867
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff818e94b0-ffffffff818e99f2: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:834
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff8193f7e0-ffffffff8193fcc5: vif_add (STB_LOCAL)
ffffffff8194406d-ffffffff81944079: vif_add.cold.67 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:837
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff8196f820-ffffffff8196fd07: vif_add (STB_LOCAL)
ffffffff819741bd-ffffffff819741c9: vif_add.cold.68 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff819d9090-ffffffff819d95fe: vif_add (STB_LOCAL)
ffffffff819ddc6c-ffffffff819ddc78: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a0fe00-ffffffff81a1036e: vif_add (STB_LOCAL)
ffffffff81a14da9-ffffffff81a14db5: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:805
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b00e30-ffffffff81b01345: vif_add (STB_LOCAL)
ffffffff81b05d2b-ffffffff81b05d37: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:808
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81b0ef10-ffffffff81b0f425: vif_add (STB_LOCAL)
ffffffff81c32a29-ffffffff81c32a35: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:808
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81afcc20-ffffffff81afd124: vif_add (STB_LOCAL)
ffffffff81c24d22-ffffffff81c24d2e: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:810
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81bbe3b0-ffffffff81bbe919: vif_add (STB_LOCAL)
ffffffff81d3e9f0-ffffffff81d3ea10: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:803
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81d532e0-ffffffff81d53867: vif_add (STB_LOCAL)
ffffffff81f0b31b-ffffffff81f0b33b: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:810
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f1cf90-ffffffff81f1d5a0: vif_add (STB_LOCAL)
ffffffff820b2bc5-ffffffff820b2c0f: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:810
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81f7ca70-ffffffff81f7d094: vif_add (STB_LOCAL)
ffffffff82133d7d-ffffffff82133dc7: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:810
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff82043170-ffffffff82043794: vif_add (STB_LOCAL)
ffffffff82215789-ffffffff822157d3: vif_add.cold (STB_LOCAL)
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
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccd360)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffff800010ccd360-ffff800010ccd85c: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd5110)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
c0dd5110-c0dd55a0: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000dec610)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
c000000000dec610-c000000000decc2c: vif_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe00081ddd0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffe00081ddd0-ffffffe00081e200: vif_add (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff819af820-ffffffff819afd8e: vif_add (STB_LOCAL)
ffffffff819b443c-ffffffff819b4448: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff8196be50-ffffffff8196c3be: vif_add (STB_LOCAL)
ffffffff81970a6c-ffffffff81970a78: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a1a0c0-ffffffff81a1a62e: vif_add (STB_LOCAL)
ffffffff81a1ecdc-ffffffff81a1ece8: vif_add.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int vif_add(struct net *net, struct mr_table *mrt, struct vifctl *vifc, int mrtsock);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:831
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ip_mroute_setsockopt
```
**Symbols:**

```
ffffffff81a24ef0-ffffffff81a2545e: vif_add (STB_LOCAL)
ffffffff81a2a19e-ffffffff81a2a1aa: vif_add.cold (STB_LOCAL)
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
