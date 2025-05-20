# Function: <code>devm_register_netdev</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff819dd700)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff819dd700-ffffffff819dd7a7: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff819dd100)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff819dd100-ffffffff819dd1a7: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff819c3350)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff819c3350-ffffffff819c33f7: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81a72c00)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff81a72c00-ffffffff81a72cae: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81be53b0)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff81be53b0-ffffffff81be548f: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81d915c0)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff81d915c0-ffffffff81d9169f: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81dff890)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff81dff890-ffffffff81dff96f: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_register_netdev(struct device *dev, struct net_device *ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81ebbd70)
Location: net/devres.c:67
Inline: False
```
**Symbols:**

```
ffffffff81ebbd70-ffffffff81ebbe4f: devm_register_netdev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
