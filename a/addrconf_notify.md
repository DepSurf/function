# Function: <code>addrconf_notify</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff817d1540)
Location: net/ipv6/addrconf.c:3140
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff817d1540-ffffffff817d1f05: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff8183ed70)
Location: net/ipv6/addrconf.c:3296
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff8183ed70-ffffffff8183f8da: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81870980)
Location: net/ipv6/addrconf.c:3312
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81870980-ffffffff8187150b: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81895750)
Location: net/ipv6/addrconf.c:3381
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81895750-ffffffff8189626b: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81916bf0)
Location: net/ipv6/addrconf.c:3368
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81916bf0-ffffffff81917629: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3423
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff8196e2a0-ffffffff8196ed66: addrconf_notify (STB_LOCAL)
ffffffff8196f484-ffffffff8196f4c2: addrconf_notify.cold.81 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3439
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff819a3e20-ffffffff819a491e: addrconf_notify (STB_LOCAL)
ffffffff819a5034-ffffffff819a505d: addrconf_notify.cold.83 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3477
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81a10170-ffffffff81a10c7d: addrconf_notify (STB_LOCAL)
ffffffff81a114aa-ffffffff81a114e6: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81a46eb0-ffffffff81a479bd: addrconf_notify (STB_LOCAL)
ffffffff81a480e3-ffffffff81a4811f: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3e48f)
Location: net/ipv6/addrconf.c:3448
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81b3dda0-ffffffff81b3e442: addrconf_notify (STB_LOCAL)
ffffffff81b3ebc9-ffffffff81b3ec0b: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b4d01f)
Location: net/ipv6/addrconf.c:3475
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81b4c930-ffffffff81b4cfd2: addrconf_notify (STB_LOCAL)
ffffffff81c32c73-ffffffff81c32cb5: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81b3ae1f)
Location: net/ipv6/addrconf.c:3477
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81b3a600-ffffffff81b3add8: addrconf_notify (STB_LOCAL)
ffffffff81c24f99-ffffffff81c24fc7: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81c0160f)
Location: net/ipv6/addrconf.c:3507
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81c00da0-ffffffff81c015c1: addrconf_notify (STB_LOCAL)
ffffffff81d3faaa-ffffffff81d3fb41: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81d9b2cf)
Location: net/ipv6/addrconf.c:3514
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81d9aa90-ffffffff81d9b289: addrconf_notify (STB_LOCAL)
ffffffff81f0c41f-ffffffff81f0c4b6: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81f69eef)
Location: net/ipv6/addrconf.c:3538
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81f69900-ffffffff81f69e9e: addrconf_notify (STB_LOCAL)
ffffffff820b3b61-ffffffff820b3b76: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff81fc9f2f)
Location: net/ipv6/addrconf.c:3543
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81fc9970-ffffffff81fc9eda: addrconf_notify (STB_LOCAL)
ffffffff82134c52-ffffffff82134c67: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (ffffffff820976bf)
Location: net/ipv6/addrconf.c:3594
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:dev_disable_change
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff82097110-ffffffff82097668: addrconf_notify (STB_LOCAL)
ffffffff82216716-ffffffff8221672b: addrconf_notify.cold (STB_LOCAL)
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
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffff800010d09a90)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffff800010d09a90-ffff800010d0a488: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c0e10144)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
c0e10144-c0e10bfc: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (c000000000e34370)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
c000000000e34370-c000000000e35100: addrconf_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/addrconf.c (ffffffe0008516be)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffe0008516be-ffffffe000851ff2: addrconf_notify (STB_LOCAL)
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
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff819e6540-ffffffff819e704d: addrconf_notify (STB_LOCAL)
ffffffff819e7773-ffffffff819e77af: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff819a3300-ffffffff819a3e0d: addrconf_notify (STB_LOCAL)
ffffffff819a4533-ffffffff819a456f: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81a50fc0-ffffffff81a51acd: addrconf_notify (STB_LOCAL)
ffffffff81a521f3-ffffffff81a5222f: addrconf_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int addrconf_notify(struct notifier_block *this, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv6/addrconf.c (0)
Location: net/ipv6/addrconf.c:3483
Inline: False
Direct callers:
  - net/ipv6/addrconf.c:dev_disable_change
  - net/ipv6/addrconf.c:dev_disable_change
```
**Symbols:**

```
ffffffff81a5cf10-ffffffff81a5da29: addrconf_notify (STB_LOCAL)
ffffffff81a5e143-ffffffff81a5e17f: addrconf_notify.cold (STB_LOCAL)
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
