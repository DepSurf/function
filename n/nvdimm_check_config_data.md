# Function: <code>nvdimm_check_config_data</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8161b5d0)
Location: drivers/nvdimm/dimm_devs.c:31
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff8161b5d0-ffffffff8161b61d: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8162f680)
Location: drivers/nvdimm/dimm_devs.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff8162f680-ffffffff8162f6cd: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81697e60)
Location: drivers/nvdimm/dimm_devs.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81697e60-ffffffff81697ead: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816d3fb0)
Location: drivers/nvdimm/dimm_devs.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff816d3fb0-ffffffff816d3ffd: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816f5a10)
Location: drivers/nvdimm/dimm_devs.c:32
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff816f5a10-ffffffff816f5a5d: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (0)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81730142-ffffffff81730154: nvdimm_check_config_data.cold (STB_LOCAL)
ffffffff8172f220-ffffffff8172f260: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81753650)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81753650-ffffffff8175369b: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81811dfd)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff818121f0-ffffffff81812230: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818210ad)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81821440-ffffffff81821480: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff818043ad)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81804770-ffffffff818047b0: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff8188e84d)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff8188eda0-ffffffff8188ede0: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff819d7ee1)
Location: drivers/nvdimm/dimm_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff819d8280-ffffffff819d82c8: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81b52d81)
Location: drivers/nvdimm/dimm_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81b53140-ffffffff81b53188: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81ba6221)
Location: drivers/nvdimm/dimm_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81ba65e0-ffffffff81ba6628: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81bfa4a1)
Location: drivers/nvdimm/dimm_devs.c:25
Inline: True
Inline callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81bfa890-ffffffff81bfa8d8: nvdimm_check_config_data (STB_GLOBAL)
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
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffff800010953f50)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffff800010953f50-ffff800010953fbc: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (c000000000a01410)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
c000000000a01410-c000000000a01484: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffe0005c37d0)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffe0005c37d0-ffffffe0005c3830: nvdimm_check_config_data (STB_GLOBAL)
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
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81707d40)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81707d40-ffffffff81707d8b: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff816db7c0)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff816db7c0-ffffffff816db80b: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81746b10)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81746b10-ffffffff81746b5b: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int nvdimm_check_config_data(struct device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/nvdimm/dimm_devs.c (ffffffff81761f50)
Location: drivers/nvdimm/dimm_devs.c:29
Inline: False
Direct callers:
  - drivers/nvdimm/dimm_devs.c:validate_dimm
```
**Symbols:**

```
ffffffff81761f50-ffffffff81761f9b: nvdimm_check_config_data (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
