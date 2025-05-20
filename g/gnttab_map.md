# Function: <code>gnttab_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff814c4d00)
Location: drivers/xen/grant-table.c:958
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff814c4d00-ffffffff814c4e36: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81515480)
Location: drivers/xen/grant-table.c:957
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81515480-ffffffff815155bc: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81541910)
Location: drivers/xen/grant-table.c:957
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81541910-ffffffff81541a4c: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81555760)
Location: drivers/xen/grant-table.c:958
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81555760-ffffffff8155589c: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff815b93b0)
Location: drivers/xen/grant-table.c:1105
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff815b93b0-ffffffff815b94f3: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1105
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff815f2ad0-ffffffff815f2c0e: gnttab_map (STB_LOCAL)
ffffffff815f345e-ffffffff815f3471: gnttab_map.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff8160d2a0-ffffffff8160d3de: gnttab_map (STB_LOCAL)
ffffffff8160e434-ffffffff8160e447: gnttab_map.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81640ce0-ffffffff81640e1e: gnttab_map (STB_LOCAL)
ffffffff8164214e-ffffffff81642161: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff816636a0-ffffffff816637de: gnttab_map (STB_LOCAL)
ffffffff8166470e-ffffffff81664721: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1230
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
```
**Symbols:**

```
ffffffff81712320-ffffffff81712462: gnttab_map (STB_LOCAL)
ffffffff81713c99-ffffffff81713cac: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1353
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
```
**Symbols:**

```
ffffffff8172f0b0-ffffffff8172f1f2: gnttab_map (STB_LOCAL)
ffffffff81c04aa5-ffffffff81c04ab8: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1353
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81712b00-ffffffff81712c42: gnttab_map (STB_LOCAL)
ffffffff81bf6655-ffffffff81bf6668: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1360
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff8178f5c0-ffffffff8178f702: gnttab_map (STB_LOCAL)
ffffffff81cf52b9-ffffffff81cf52cc: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1426
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
```
**Symbols:**

```
ffffffff818c7a40-ffffffff818c7bbc: gnttab_map (STB_LOCAL)
ffffffff81ebd454-ffffffff81ebd467: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a18620)
Location: drivers/xen/grant-table.c:1429
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/grant-table.c:gnttab_setup
```
**Symbols:**

```
ffffffff81a18620-ffffffff81a1879a: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81a616a0)
Location: drivers/xen/grant-table.c:1447
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/grant-table.c:gnttab_setup
```
**Symbols:**

```
ffffffff81a616a0-ffffffff81a6181a: gnttab_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffffffff81ab3ed0)
Location: drivers/xen/grant-table.c:1445
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_expand
  - drivers/xen/grant-table.c:gnttab_setup
```
**Symbols:**

```
ffffffff81ab3ed0-ffffffff81ab404a: gnttab_map (STB_LOCAL)
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
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/grant-table.c (ffff80001082c0c8)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffff80001082c0c8-ffff80001082c244: gnttab_map (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81629510-ffffffff8162964e: gnttab_map (STB_LOCAL)
ffffffff8162a57e-ffffffff8162a591: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff816574e0-ffffffff8165761e: gnttab_map (STB_LOCAL)
ffffffff8165854e-ffffffff81658561: gnttab_map.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int gnttab_map(unsigned int start_idx, unsigned int end_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/grant-table.c (0)
Location: drivers/xen/grant-table.c:1233
Inline: False
Direct callers:
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:gnttab_setup
  - drivers/xen/grant-table.c:get_free_entries
```
**Symbols:**

```
ffffffff81671ae0-ffffffff81671c1e: gnttab_map (STB_LOCAL)
ffffffff81672b4e-ffffffff81672b61: gnttab_map.cold (STB_LOCAL)
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
