# Function: <code>gnttab_batch_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c6110)
Location: drivers/xen/grant-table.c:753
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
```
**Symbols:**

```
ffffffff814c6110-ffffffff814c61e2: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815168d0)
Location: drivers/xen/grant-table.c:752
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
```
**Symbols:**

```
ffffffff815168d0-ffffffff815169a2: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81542d40)
Location: drivers/xen/grant-table.c:752
Inline: True
Direct callers:
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
  - drivers/xen/xenbus/xenbus_client.c:__xenbus_map_ring
```
**Symbols:**

```
ffffffff81542d40-ffffffff81542e12: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81556c00)
Location: drivers/xen/grant-table.c:753
Inline: True
```
**Symbols:**

```
ffffffff81556c00-ffffffff81556cca: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815baaf0)
Location: drivers/xen/grant-table.c:845
Inline: True
```
**Symbols:**

```
ffffffff815baaf0-ffffffff815babb9: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815f26c0)
Location: drivers/xen/grant-table.c:845
Inline: True
```
**Symbols:**

```
ffffffff815f26c0-ffffffff815f2782: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8160dd80)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffffffff8160dd80-ffffffff8160de42: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81641fbc)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffffffff8164229b-ffffffff816422c0: gnttab_batch_map.cold (STB_LOCAL)
ffffffff81641f20-ffffffff81641fcc: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816644bc)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffffffff81664834-ffffffff81664859: gnttab_batch_map.cold (STB_LOCAL)
ffffffff81664420-ffffffff816644cc: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8171318c)
Location: drivers/xen/grant-table.c:956
Inline: True
```
**Symbols:**

```
ffffffff81713dcd-ffffffff81713df2: gnttab_batch_map.cold (STB_LOCAL)
ffffffff817130f0-ffffffff8171319d: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8172fecc)
Location: drivers/xen/grant-table.c:1079
Inline: True
```
**Symbols:**

```
ffffffff81c04bb4-ffffffff81c04bd9: gnttab_batch_map.cold (STB_LOCAL)
ffffffff8172fe30-ffffffff8172fedd: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff817139df)
Location: drivers/xen/grant-table.c:1079
Inline: True
```
**Symbols:**

```
ffffffff81bf680c-ffffffff81bf6831: gnttab_batch_map.cold (STB_LOCAL)
ffffffff81713930-ffffffff817139f0: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1086
Inline: False
```
**Symbols:**

```
ffffffff81cf5306-ffffffff81cf532b: gnttab_batch_map.cold (STB_LOCAL)
ffffffff8178fc50-ffffffff8178fd10: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1152
Inline: False
```
**Symbols:**

```
ffffffff81ebd495-ffffffff81ebd4c3: gnttab_batch_map.cold (STB_LOCAL)
ffffffff818c7d80-ffffffff818c7e33: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a18930)
Location: drivers/xen/grant-table.c:1155
Inline: False
```
**Symbols:**

```
ffffffff81a18930-ffffffff81a18a0d: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a619b0)
Location: drivers/xen/grant-table.c:1173
Inline: False
```
**Symbols:**

```
ffffffff81a619b0-ffffffff81a61a8d: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab41e0)
Location: drivers/xen/grant-table.c:1171
Inline: False
```
**Symbols:**

```
ffffffff81ab41e0-ffffffff81ab42bd: gnttab_batch_map (STB_GLOBAL)
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
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082c870)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffff80001082c870-ffff80001082c978: gnttab_batch_map (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff8162a32c)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffffffff8162a6a4-ffffffff8162a6c9: gnttab_batch_map.cold (STB_LOCAL)
ffffffff8162a290-ffffffff8162a33c: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816582fc)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffffffff81658674-ffffffff81658699: gnttab_batch_map.cold (STB_LOCAL)
ffffffff81658260-ffffffff8165830c: gnttab_batch_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void gnttab_batch_map(struct gnttab_map_grant_ref *batch, unsigned int count);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff816728fc)
Location: drivers/xen/grant-table.c:958
Inline: True
```
**Symbols:**

```
ffffffff81672c74-ffffffff81672c99: gnttab_batch_map.cold (STB_LOCAL)
ffffffff81672860-ffffffff8167290c: gnttab_batch_map (STB_GLOBAL)
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
