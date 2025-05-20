# Function: <code>ncsi_channel_is_tx</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819ffdd0)
Location: net/ncsi/ncsi-manage.c:782
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff819ffdd0-ffffffff819ffeee: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a6f0e0)
Location: net/ncsi/ncsi-manage.c:778
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81a6f0e0-ffffffff81a6f1f4: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81aa5970)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81aa5970-ffffffff81aa5a84: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ba1350)
Location: net/ncsi/ncsi-manage.c:804
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81ba1350-ffffffff81ba1468: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81bb0c10)
Location: net/ncsi/ncsi-manage.c:804
Inline: False
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81bb0c10-ffffffff81bb0d28: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81b9fe30)
Location: net/ncsi/ncsi-manage.c:810
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81b9fe30-ffffffff81b9ff48: ncsi_channel_is_tx.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:862
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81c6d790-ffffffff81c6d8c8: ncsi_channel_is_tx.constprop.0 (STB_LOCAL)
ffffffff81d42676-ffffffff81d4268b: ncsi_channel_is_tx.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:862
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81e11380-ffffffff81e114c4: ncsi_channel_is_tx.constprop.0 (STB_LOCAL)
ffffffff81f0f034-ffffffff81f0f049: ncsi_channel_is_tx.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:862
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81fe7d50-ffffffff81fe7e94: ncsi_channel_is_tx.constprop.0 (STB_LOCAL)
ffffffff820b597e-ffffffff820b5993: ncsi_channel_is_tx.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:862
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff82063fd0-ffffffff82064114: ncsi_channel_is_tx.constprop.0 (STB_LOCAL)
ffffffff82136f01-ffffffff82136f16: ncsi_channel_is_tx.constprop.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:854
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff82137110-ffffffff82137254: ncsi_channel_is_tx.constprop.0 (STB_LOCAL)
ffffffff82218d63-ffffffff82218d78: ncsi_channel_is_tx.constprop.0.cold (STB_LOCAL)
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
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d77e70)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffff800010d77e70-ffff800010d77f8c: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e74134)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
c0e74134-c0e74258: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb7ae0)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
c000000000eb7ae0-c000000000eb7c14: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a7760)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffe0008a7760-ffffffe0008a7844: ncsi_channel_is_tx (STB_LOCAL)
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
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a44d00)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81a44d00-ffffffff81a44e14: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a018f0)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81a018f0-ffffffff81a01a04: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81ab0bb0)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81ab0bb0-ffffffff81ab0cc4: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ncsi_channel_is_tx(struct ncsi_dev_priv *ndp, struct ncsi_channel *nc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81abcf60)
Location: net/ncsi/ncsi-manage.c:777
Inline: True
Direct callers:
  - net/ncsi/ncsi-manage.c:ncsi_configure_channel
```
**Symbols:**

```
ffffffff81abcf60-ffffffff81abd074: ncsi_channel_is_tx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
