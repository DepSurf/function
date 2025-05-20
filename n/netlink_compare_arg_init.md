# Function: <code>netlink_compare_arg_init</code>

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
In net/netlink/af_netlink.c (ffffffff8174b867)
Location: net/netlink/af_netlink.c:1038
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:netlink_insert
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
In net/netlink/af_netlink.c (ffffffff817b8847)
Location: net/netlink/af_netlink.c:424
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:netlink_lookup
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
In net/netlink/af_netlink.c (ffffffff817e82f7)
Location: net/netlink/af_netlink.c:431
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81806c90)
Location: net/netlink/af_netlink.c:462
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81806c90-ffffffff81806ca8: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81885970)
Location: net/netlink/af_netlink.c:464
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81885970-ffffffff81885988: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818d9310)
Location: net/netlink/af_netlink.c:498
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff818d9310-ffffffff818d9328: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81905b00)
Location: net/netlink/af_netlink.c:498
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81905b00-ffffffff81905b18: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81966d50)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff81966d50-ffffffff81966d68: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8199d7d0)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff8199d7d0-ffffffff8199d7e8: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a77d7b)
Location: net/netlink/af_netlink.c:489
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a80c4b)
Location: net/netlink/af_netlink.c:490
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81a6a2d5)
Location: net/netlink/af_netlink.c:500
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81b238d4)
Location: net/netlink/af_netlink.c:500
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81cac2f1)
Location: net/netlink/af_netlink.c:504
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81f05b99-ffffffff81f05bae: netlink_compare_arg_init.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81e69ed1)
Location: net/netlink/af_netlink.c:504
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81ec30c0)
Location: net/netlink/af_netlink.c:504
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81ec30c0-ffffffff81ec30e2: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff81f86410)
Location: net/netlink/af_netlink.c:502
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_insert
```
**Symbols:**

```
ffffffff81f86410-ffffffff81f8643a: netlink_compare_arg_init (STB_LOCAL)
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
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffff800010c4ac88)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffff800010c4ac88-ffff800010c4acc4: netlink_compare_arg_init (STB_LOCAL)
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
In net/netlink/af_netlink.c (c0d5df74)
Location: net/netlink/af_netlink.c:489
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:netlink_autobind
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (c000000000d48dd0)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
c000000000d48dd0-c000000000d48dec: netlink_compare_arg_init (STB_LOCAL)
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
In net/netlink/af_netlink.c (ffffffe0007b8980)
Location: net/netlink/af_netlink.c:489
Inline: True
Inline callers:
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
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
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8193d640)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff8193d640-ffffffff8193d658: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff818f7140)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff818f7140-ffffffff818f7158: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff8198e7d0)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:__netlink_insert
  - net/netlink/af_netlink.c:__netlink_lookup
```
**Symbols:**

```
ffffffff8198e7d0-ffffffff8198e7e8: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void netlink_compare_arg_init(struct netlink_compare_arg *arg, struct net *net, u32 portid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/netlink/af_netlink.c (ffffffff819b1080)
Location: net/netlink/af_netlink.c:489
Inline: False
Direct callers:
  - net/netlink/af_netlink.c:netlink_hash
  - net/netlink/af_netlink.c:netlink_lookup
  - net/netlink/af_netlink.c:__netlink_insert
```
**Symbols:**

```
ffffffff819b1080-ffffffff819b1098: netlink_compare_arg_init (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
