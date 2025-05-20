# Function: <code>change_proto_down</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81735550)
Location: net/core/net-sysfs.c:406
Inline: False
```
**Symbols:**

```
ffffffff81735550-ffffffff8173556b: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817a16a0)
Location: net/core/net-sysfs.c:422
Inline: False
```
**Symbols:**

```
ffffffff817a16a0-ffffffff817a16bb: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817cffc0)
Location: net/core/net-sysfs.c:422
Inline: False
```
**Symbols:**

```
ffffffff817cffc0-ffffffff817cffdb: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff817ef3c0)
Location: net/core/net-sysfs.c:427
Inline: False
```
**Symbols:**

```
ffffffff817ef3c0-ffffffff817ef3db: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff8186a960)
Location: net/core/net-sysfs.c:438
Inline: False
```
**Symbols:**

```
ffffffff8186a960-ffffffff8186a97b: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818bb7e0)
Location: net/core/net-sysfs.c:436
Inline: False
```
**Symbols:**

```
ffffffff818bb7e0-ffffffff818bb7fb: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818e28a0)
Location: net/core/net-sysfs.c:437
Inline: False
```
**Symbols:**

```
ffffffff818e28a0-ffffffff818e28bb: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81931e80)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffff81931e80-ffffffff81931e9b: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819649c0)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffff819649c0-ffffffff819649db: change_proto_down (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81a39a63)
Location: net/core/net-sysfs.c:461
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_store
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
In net/core/net-sysfs.c (ffffffff81a3bd13)
Location: net/core/net-sysfs.c:462
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_store
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81a20c30)
Location: net/core/net-sysfs.c:462
Inline: False
```
**Symbols:**

```
ffffffff81a20c30-ffffffff81a20c4b: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81ad50b0)
Location: net/core/net-sysfs.c:482
Inline: False
```
**Symbols:**

```
ffffffff81ad50b0-ffffffff81ad50cb: change_proto_down (STB_LOCAL)
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
In net/core/net-sysfs.c (ffffffff81c57fb6)
Location: net/core/net-sysfs.c:484
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_store
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
In net/core/net-sysfs.c (ffffffff81e0dce6)
Location: net/core/net-sysfs.c:484
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_store
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
In net/core/net-sysfs.c (ffffffff81e80f36)
Location: net/core/net-sysfs.c:484
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_store
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
In net/core/net-sysfs.c (ffffffff81f41ff9)
Location: net/core/net-sysfs.c:496
Inline: True
Inline callers:
  - net/core/net-sysfs.c:proto_down_store
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
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffff800010c094c8)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffff800010c094c8-ffff800010c09500: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c0d222d4)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
c0d222d4-c0d222f8: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (c000000000cf4160)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
c000000000cf4160-c000000000cf419c: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffe0007871b4)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffe0007871b4-ffffffe0007871e8: change_proto_down (STB_LOCAL)
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
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81904990)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffff81904990-ffffffff819049ab: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff818be7c0)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffff818be7c0-ffffffff818be7db: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff819559c0)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffff819559c0-ffffffff819559db: change_proto_down (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int change_proto_down(struct net_device *dev, long unsigned int proto_down);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/net-sysfs.c (ffffffff81977a20)
Location: net/core/net-sysfs.c:432
Inline: False
```
**Symbols:**

```
ffffffff81977a20-ffffffff81977a3b: change_proto_down (STB_LOCAL)
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
