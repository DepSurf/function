# Function: <code>devm_mdiobus_unregister</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff8188d450)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff8188d450-ffffffff8188d463: devm_mdiobus_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff8186fd90)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff8186fd90-ffffffff8186fda3: devm_mdiobus_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff81900370)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81900370-ffffffff81900383: devm_mdiobus_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff81a51ee0)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81a51ee0-ffffffff81a51efb: devm_mdiobus_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff81bdb280)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81bdb280-ffffffff81bdb29b: devm_mdiobus_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff81c31d30)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81c31d30-ffffffff81c31d4b: devm_mdiobus_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_mdiobus_unregister(struct device *dev, void *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/mdio_devres.c (ffffffff81ce6a20)
Location: drivers/net/phy/mdio_devres.c:49
Inline: False
```
**Symbols:**

```
ffffffff81ce6a20-ffffffff81ce6a3b: devm_mdiobus_unregister (STB_LOCAL)
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
