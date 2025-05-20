# Function: <code>ppp_unit_register</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81656098)
Location: drivers/net/ppp/ppp_generic.c:970
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
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
In drivers/net/ppp/ppp_generic.c (ffffffff81683d78)
Location: drivers/net/ppp/ppp_generic.c:970
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81699373)
Location: drivers/net/ppp/ppp_generic.c:972
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81706167)
Location: drivers/net/ppp/ppp_generic.c:975
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81743f34)
Location: drivers/net/ppp/ppp_generic.c:958
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81766ae4)
Location: drivers/net/ppp/ppp_generic.c:958
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817a5938)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817c7f98)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
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
In drivers/net/ppp/ppp_generic.c (ffffffff81891a38)
Location: drivers/net/ppp/ppp_generic.c:1040
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
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
In drivers/net/ppp/ppp_generic.c (ffffffff8189fcf8)
Location: drivers/net/ppp/ppp_generic.c:1150
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ppp_unit_register(struct ppp *ppp, int unit, bool ifname_is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff818825e0)
Location: drivers/net/ppp/ppp_generic.c:1150
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
**Symbols:**

```
ffffffff818825e0-ffffffff81882778: ppp_unit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ppp_unit_register(struct ppp *ppp, int unit, bool ifname_is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81913f30)
Location: drivers/net/ppp/ppp_generic.c:1155
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
**Symbols:**

```
ffffffff81913f30-ffffffff819140c8: ppp_unit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ppp_unit_register(struct ppp *ppp, int unit, bool ifname_is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81a694b0)
Location: drivers/net/ppp/ppp_generic.c:1156
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
**Symbols:**

```
ffffffff81a694b0-ffffffff81a69665: ppp_unit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ppp_unit_register(struct ppp *ppp, int unit, bool ifname_is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81bfbff0)
Location: drivers/net/ppp/ppp_generic.c:1156
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
**Symbols:**

```
ffffffff81bfbff0-ffffffff81bfc1a5: ppp_unit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ppp_unit_register(struct ppp *ppp, int unit, bool ifname_is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81c61670)
Location: drivers/net/ppp/ppp_generic.c:1156
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
**Symbols:**

```
ffffffff81c61670-ffffffff81c61825: ppp_unit_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ppp_unit_register(struct ppp *ppp, int unit, bool ifname_is_set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81d18050)
Location: drivers/net/ppp/ppp_generic.c:1156
Inline: False
Direct callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
**Symbols:**

```
ffffffff81d18050-ffffffff81d1821d: ppp_unit_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffff8000109feb48)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c0add41c)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (c000000000aa83d4)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffe00062cd18)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff8178ca78)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff81775848)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817bce18)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/ppp/ppp_generic.c (ffffffff817d7a28)
Location: drivers/net/ppp/ppp_generic.c:954
Inline: True
Inline callers:
  - drivers/net/ppp/ppp_generic.c:ppp_dev_configure
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
