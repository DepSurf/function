# Function: <code>ipmr_rules_exit</code>

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
In net/ipv4/ipmr.c (ffffffff817a8bc5)
Location: net/ipv4/ipmr.c:308
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
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
In net/ipv4/ipmr.c (ffffffff818163b5)
Location: net/ipv4/ipmr.c:288
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
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
In net/ipv4/ipmr.c (ffffffff81847b65)
Location: net/ipv4/ipmr.c:293
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
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
In net/ipv4/ipmr.c (ffffffff8186b5e3)
Location: net/ipv4/ipmr.c:294
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
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
In net/ipv4/ipmr.c (ffffffff818ebdda)
Location: net/ipv4/ipmr.c:311
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff819425ea)
Location: net/ipv4/ipmr.c:334
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff819723da)
Location: net/ipv4/ipmr.c:337
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff819dbdfa)
Location: net/ipv4/ipmr.c:331
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a12cf0)
Location: net/ipv4/ipmr.c:268
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff81a12cf0-ffffffff81a12d72: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b04130)
Location: net/ipv4/ipmr.c:270
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
```
**Symbols:**

```
ffffffff81b04130-ffffffff81b041ed: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81b122a0)
Location: net/ipv4/ipmr.c:270
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
```
**Symbols:**

```
ffffffff81b122a0-ffffffff81b1235d: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81aff9f0)
Location: net/ipv4/ipmr.c:270
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
```
**Symbols:**

```
ffffffff81aff9f0-ffffffff81affaad: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81bc17f0)
Location: net/ipv4/ipmr.c:272
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
```
**Symbols:**

```
ffffffff81bc17f0-ffffffff81bc18ad: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:267
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
```
**Symbols:**

```
ffffffff81d56d50-ffffffff81d56e5a: ipmr_rules_exit (STB_LOCAL)
ffffffff81f0b422-ffffffff81f0b436: ipmr_rules_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:272
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
```
**Symbols:**

```
ffffffff81f21640-ffffffff81f2174a: ipmr_rules_exit (STB_LOCAL)
ffffffff820b2cf9-ffffffff820b2d0d: ipmr_rules_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:272
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
```
**Symbols:**

```
ffffffff81f808d0-ffffffff81f809da: ipmr_rules_exit (STB_LOCAL)
ffffffff82133e89-ffffffff82133e9d: ipmr_rules_exit.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/ipmr.c (0)
Location: net/ipv4/ipmr.c:272
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit_batch
```
**Symbols:**

```
ffffffff82046f50-ffffffff8204705a: ipmr_rules_exit (STB_LOCAL)
ffffffff82215895-ffffffff822158a9: ipmr_rules_exit.cold (STB_LOCAL)
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
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffff800010ccc470)
Location: net/ipv4/ipmr.c:268
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffff800010ccc470-ffff800010ccc4fc: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c0dd826c)
Location: net/ipv4/ipmr.c:268
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
c0dd826c-c0dd82e0: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (c000000000deb970)
Location: net/ipv4/ipmr.c:268
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
c000000000deb970-c000000000deba50: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffe000820ce4)
Location: net/ipv4/ipmr.c:268
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffe000820ce4-ffffffe000820d64: ipmr_rules_exit (STB_LOCAL)
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
In net/ipv4/ipmr.c (ffffffff819b25ea)
Location: net/ipv4/ipmr.c:331
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff8196ec1a)
Location: net/ipv4/ipmr.c:331
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
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
In net/ipv4/ipmr.c (ffffffff81a1ce8a)
Location: net/ipv4/ipmr.c:331
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ipmr_rules_exit(struct net *net);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ipmr.c (ffffffff81a27e70)
Location: net/ipv4/ipmr.c:268
Inline: False
Direct callers:
  - net/ipv4/ipmr.c:ipmr_net_exit
  - net/ipv4/ipmr.c:ipmr_net_init
```
**Symbols:**

```
ffffffff81a27e70-ffffffff81a27ef2: ipmr_rules_exit (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
