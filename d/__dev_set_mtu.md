# Function: <code>__dev_set_mtu</code>

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
In net/core/dev.c (ffffffff81714910)
Location: net/core/dev.c:6010
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
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
In net/core/dev.c (ffffffff8177c8a0)
Location: net/core/dev.c:6461
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
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
In net/core/dev.c (ffffffff817aad77)
Location: net/core/dev.c:6605
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c93da)
Location: net/core/dev.c:6770
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
```
**Symbols:**

```
ffffffff817c7620-ffffffff817c7646: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81843083)
Location: net/core/dev.c:6934
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
```
**Symbols:**

```
ffffffff81841200-ffffffff81841229: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188d4af)
Location: net/core/dev.c:7070
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu
  - net/core/dev.c:dev_set_mtu
```
**Symbols:**

```
ffffffff8188b910-ffffffff8188b939: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818b9039)
Location: net/core/dev.c:7648
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff818aca90-ffffffff818acab9: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819051e9)
Location: net/core/dev.c:7658
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff818f8210-ffffffff818f8239: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819378a9)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff8192a3a0-ffffffff8192a3c9: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0c3f8)
Location: net/core/dev.c:8360
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff819fe260-ffffffff819fe289: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0dac8)
Location: net/core/dev.c:8605
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff819fde70-ffffffff819fde99: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819f47a1)
Location: net/core/dev.c:8864
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff819e4730-ffffffff819e4759: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81aa60d1)
Location: net/core/dev.c:8854
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff81a95210-ffffffff81a9523c: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c1dbab)
Location: net/core/dev.c:8619
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff81c0b880-ffffffff81c0b8bc: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dceed7)
Location: net/core/dev.c:8606
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff81dbb880-ffffffff81dbb8bc: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e3fb0b)
Location: net/core/dev.c:8612
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff81e2c010-ffffffff81e2c04c: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81efe465)
Location: net/core/dev.c:8730
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff81eea060-ffffffff81eea096: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bd62f0)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffff800010bc6d08-ffff800010bc6d5c: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0cf0e8c)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
c0ce216c-c0ce21a8: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000cb5bec)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
c000000000ca1970-c000000000ca19d4: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe00075faa8)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffe00075322c-ffffffe000753276: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818d7879)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff818ca3a0-ffffffff818ca3c9: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818916b9)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff818842e0-ffffffff81884309: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819288a9)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff8191b3a0-ffffffff8191b3c9: __dev_set_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int __dev_set_mtu(struct net_device *dev, int new_mtu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81949f79)
Location: net/core/dev.c:7947
Inline: True
Inline callers:
  - net/core/dev.c:dev_set_mtu_ext
  - net/core/dev.c:dev_set_mtu_ext
```
**Symbols:**

```
ffffffff8193c5a0-ffffffff8193c5c9: __dev_set_mtu (STB_GLOBAL)
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
