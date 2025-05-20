# Function: <code>ncsi_update_tx_channel</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff81a00f80)
Location: net/ncsi/ncsi-manage.c:824
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81a00f80-ffffffff81a01239: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:820
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81a71e50-ffffffff81a71eda: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81a70140-ffffffff81a7037b: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81aa8614-ffffffff81aa869e: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81aa6970-ffffffff81aa6bab: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:846
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81ba451a-ffffffff81ba45a4: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81ba27f0-ffffffff81ba2a2b: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:846
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81c33988-ffffffff81c33a12: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81bb2070-ffffffff81bb22ab: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:852
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81c25ca7-ffffffff81c25d26: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81ba1090-ffffffff81ba12d0: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:904
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81d42739-ffffffff81d428f7: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81c6ea90-ffffffff81c6ed34: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:904
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81f0f0de-ffffffff81f0f2b6: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81e12640-ffffffff81e128d2: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:904
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff820b5a28-ffffffff820b5b1d: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81fe90d0-ffffffff81fe93e6: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:904
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff82136fab-ffffffff82137092: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff82065350-ffffffff82065666: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:896
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff82218e0d-ffffffff82218ef4: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff821384f0-ffffffff82138806: ncsi_update_tx_channel (STB_GLOBAL)
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
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffff800010d79880)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffff800010d79880-ffff800010d79b50: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c0e7526c)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
c0e7526c-c0e75570: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (c000000000eb90c0)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
c000000000eb90c0-c000000000eb9440: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffe0008a870e)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffe0008a870e-ffffffe0008a8936: ncsi_update_tx_channel (STB_GLOBAL)
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
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81a479a4-ffffffff81a47a2e: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81a45d00-ffffffff81a45f3b: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81a04594-ffffffff81a0461e: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81a028f0-ffffffff81a02b2b: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81ab3854-ffffffff81ab38de: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81ab1bb0-ffffffff81ab1deb: ncsi_update_tx_channel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_update_tx_channel(struct ncsi_dev_priv *ndp, struct ncsi_package *package, struct ncsi_channel *disable, struct ncsi_channel *enable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:819
Inline: False
Direct callers:
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
  - net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc
```
**Symbols:**

```
ffffffff81abfbf4-ffffffff81abfc7e: ncsi_update_tx_channel.cold (STB_LOCAL)
ffffffff81abdf60-ffffffff81abe19b: ncsi_update_tx_channel (STB_GLOBAL)
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
