# Function: <code>addrconf_fixup_forwarding</code>

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
In net/ipv6/addrconf.c (ffffffff817cda37)
Location: net/ipv6/addrconf.c:752
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff8183ad97)
Location: net/ipv6/addrconf.c:759
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff8186c797)
Location: net/ipv6/addrconf.c:786
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff818912e7)
Location: net/ipv6/addrconf.c:799
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff81912a37)
Location: net/ipv6/addrconf.c:803
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff81969ee7)
Location: net/ipv6/addrconf.c:792
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff8199f7a7)
Location: net/ipv6/addrconf.c:806
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff81a0b986)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff81a42636)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b38050)
Location: net/ipv6/addrconf.c:840
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81b38050-ffffffff81b381f7: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b46d80)
Location: net/ipv6/addrconf.c:840
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81b46d80-ffffffff81b46f27: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b34b30)
Location: net/ipv6/addrconf.c:842
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81b34b30-ffffffff81b34cd7: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfb220)
Location: net/ipv6/addrconf.c:849
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81bfb220-ffffffff81bfb3c7: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d94960)
Location: net/ipv6/addrconf.c:859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81d94960-ffffffff81d94b29: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f63100)
Location: net/ipv6/addrconf.c:859
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81f63100-ffffffff81f632c9: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc30c0)
Location: net/ipv6/addrconf.c:858
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff81fc30c0-ffffffff81fc3289: addrconf_fixup_forwarding (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int addrconf_fixup_forwarding(struct ctl_table *table, int *p, int newf);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82090670)
Location: net/ipv6/addrconf.c:877
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
```
**Symbols:**

```
ffffffff82090670-ffffffff82090842: addrconf_fixup_forwarding (STB_LOCAL)
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
In net/ipv6/addrconf.c (ffff800010d040bc)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (c0e0b574)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (c000000000e2ded8)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffe00084d238)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff819e1cc6)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff8199ea86)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff81a4c746)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
In net/ipv6/addrconf.c (ffffffff81a586b6)
Location: net/ipv6/addrconf.c:840
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_sysctl_forward
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
