# Function: <code>devinet_sysctl_unregister</code>

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
In net/ipv4/devinet.c (ffffffff81791e23)
Location: net/ipv4/devinet.c:2259
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
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
In net/ipv4/devinet.c (ffffffff817ffbdc)
Location: net/ipv4/devinet.c:2297
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
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
In net/ipv4/devinet.c (ffffffff81830b3c)
Location: net/ipv4/devinet.c:2297
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81851ce0)
Location: net/ipv4/devinet.c:2352
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81851ce0-ffffffff81851d18: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff818d1ad0)
Location: net/ipv4/devinet.c:2361
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff818d1ad0-ffffffff818d1b08: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81927fd0)
Location: net/ipv4/devinet.c:2371
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81927fd0-ffffffff81928008: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81957230)
Location: net/ipv4/devinet.c:2531
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81957230-ffffffff81957268: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819bbc70)
Location: net/ipv4/devinet.c:2621
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff819bbc70-ffffffff819bbca8: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819f2970)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff819f2970-ffffffff819f29a8: devinet_sysctl_unregister (STB_LOCAL)
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
In net/ipv4/devinet.c (ffffffff81ae1a61)
Location: net/ipv4/devinet.c:2619
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
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
In net/ipv4/devinet.c (ffffffff81aee901)
Location: net/ipv4/devinet.c:2618
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
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
In net/ipv4/devinet.c (ffffffff81ad9e34)
Location: net/ipv4/devinet.c:2619
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
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
In net/ipv4/devinet.c (ffffffff81b98f74)
Location: net/ipv4/devinet.c:2624
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81d2ae1e)
Location: net/ipv4/devinet.c:2633
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
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
In net/ipv4/devinet.c (ffffffff81ef2ada)
Location: net/ipv4/devinet.c:2634
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81f5268b)
Location: net/ipv4/devinet.c:2637
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff82018962)
Location: net/ipv4/devinet.c:2667
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_destroy
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
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffff800010ca8c50)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffff800010ca8c50-ffff800010ca8c90: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c0db53f0)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
c0db53f0-c0db5428: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (c000000000dbdd40)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
c000000000dbdd40-c000000000dbdd98: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffe00080397c)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffe00080397c-ffffffe0008039bc: devinet_sysctl_unregister (STB_LOCAL)
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
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81992710)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81992710-ffffffff81992748: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff8194c1d0)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff8194c1d0-ffffffff8194c208: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff819fcfb0)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff819fcfb0-ffffffff819fcfe8: devinet_sysctl_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void devinet_sysctl_unregister(struct in_device *idev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/devinet.c (ffffffff81a07340)
Location: net/ipv4/devinet.c:2616
Inline: False
Direct callers:
  - net/ipv4/devinet.c:inetdev_event
  - net/ipv4/devinet.c:inetdev_event
```
**Symbols:**

```
ffffffff81a07340-ffffffff81a07378: devinet_sysctl_unregister (STB_LOCAL)
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
