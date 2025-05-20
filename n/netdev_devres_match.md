# Function: <code>netdev_devres_match</code>

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
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff819dd630)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff819dd630-ffffffff819dd643: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff819dd030)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff819dd030-ffffffff819dd043: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff819c3280)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff819c3280-ffffffff819c3293: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81a72b20)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81a72b20-ffffffff81a72b33: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81be52d0)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81be52d0-ffffffff81be52eb: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81d914b0)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81d914b0-ffffffff81d914cb: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81dff780)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81dff780-ffffffff81dff79b: netdev_devres_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int netdev_devres_match(struct device *dev, void *this, void *match_data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/devres.c (ffffffff81ebbc60)
Location: net/devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81ebbc60-ffffffff81ebbc7b: netdev_devres_match (STB_LOCAL)
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
