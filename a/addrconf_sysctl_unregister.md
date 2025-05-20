# Function: <code>addrconf_sysctl_unregister</code>

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
In net/ipv6/addrconf.c (ffffffff817cdeed)
Location: net/ipv6/addrconf.c:5813
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff8183b500)
Location: net/ipv6/addrconf.c:6104
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
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
In net/ipv6/addrconf.c (ffffffff8186cede)
Location: net/ipv6/addrconf.c:6183
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81890490)
Location: net/ipv6/addrconf.c:6463
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81890490-ffffffff818904c8: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81911be0)
Location: net/ipv6/addrconf.c:6478
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81911be0-ffffffff81911c18: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81969000)
Location: net/ipv6/addrconf.c:6598
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81969000-ffffffff81969038: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199e8e0)
Location: net/ipv6/addrconf.c:6805
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff8199e8e0-ffffffff8199e918: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a0aa10)
Location: net/ipv6/addrconf.c:6899
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a0aa10-ffffffff81a0aa48: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a416c0)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a416c0-ffffffff81a416f8: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b382d0)
Location: net/ipv6/addrconf.c:6955
Inline: False
```
**Symbols:**

```
ffffffff81b382d0-ffffffff81b38346: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b47000)
Location: net/ipv6/addrconf.c:6986
Inline: False
```
**Symbols:**

```
ffffffff81b47000-ffffffff81b47076: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b34db0)
Location: net/ipv6/addrconf.c:7020
Inline: False
```
**Symbols:**

```
ffffffff81b34db0-ffffffff81b34e26: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81bfb4a0)
Location: net/ipv6/addrconf.c:7093
Inline: False
```
**Symbols:**

```
ffffffff81bfb4a0-ffffffff81bfb516: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d94c10)
Location: net/ipv6/addrconf.c:7130
Inline: False
```
**Symbols:**

```
ffffffff81d94c10-ffffffff81d94c97: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f633d0)
Location: net/ipv6/addrconf.c:7143
Inline: False
```
**Symbols:**

```
ffffffff81f633d0-ffffffff81f63457: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc3390)
Location: net/ipv6/addrconf.c:7149
Inline: False
```
**Symbols:**

```
ffffffff81fc3390-ffffffff81fc3417: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff82090950)
Location: net/ipv6/addrconf.c:7219
Inline: False
```
**Symbols:**

```
ffffffff82090950-ffffffff820909d7: addrconf_sysctl_unregister (STB_LOCAL)
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
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d03120)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffff800010d03120-ffff800010d03160: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e0a5bc)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
c0e0a5bc-c0e0a5f4: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e2c7c0)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
c000000000e2c7c0-c000000000e2c818: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe00084c440)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffe00084c440-ffffffe00084c482: addrconf_sysctl_unregister (STB_LOCAL)
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
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff819e0d50)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff819e0d50-ffffffff819e0d88: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8199db10)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff8199db10-ffffffff8199db48: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a4b7d0)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a4b7d0-ffffffff81a4b808: addrconf_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void addrconf_sysctl_unregister(struct inet6_dev *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81a57740)
Location: net/ipv6/addrconf.c:6938
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:addrconf_ifdown
  - net/ipv6/addrconf.c:addrconf_notify
  - net/ipv6/addrconf.c:addrconf_notify
```
**Symbols:**

```
ffffffff81a57740-ffffffff81a57778: addrconf_sysctl_unregister (STB_LOCAL)
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
