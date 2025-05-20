# Function: <code>pwm_put</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff8142c780)
Location: drivers/pwm/core.c:767
Inline: False
Direct callers:
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff8142c780-ffffffff8142c7ff: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81477740)
Location: drivers/pwm/core.c:844
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/sysfs.c:unexport_store
  - drivers/pwm/sysfs.c:export_store
```
**Symbols:**

```
ffffffff81477740-ffffffff814777b2: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pwm/core.c (ffffffff81498aa0)
Location: drivers/pwm/core.c:846
Inline: False
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81498aa0-ffffffff81498b12: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff814a2e58)
Location: drivers/pwm/core.c:862
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff814a2da0-ffffffff814a2e0c: pwm_put.part.14 (STB_LOCAL)
ffffffff814a2e10-ffffffff814a2e27: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff814e1bc8)
Location: drivers/pwm/core.c:862
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff814e1b10-ffffffff814e1b7f: pwm_put.part.14 (STB_LOCAL)
ffffffff814e1b80-ffffffff814e1b97: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff815113b8)
Location: drivers/pwm/core.c:862
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81511300-ffffffff81511366: pwm_put.part.15 (STB_LOCAL)
ffffffff81511951-ffffffff81511962: pwm_put.part.15.cold.20 (STB_LOCAL)
ffffffff81511370-ffffffff81511386: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81526ac8)
Location: drivers/pwm/core.c:862
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_free
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81526a10-ffffffff81526a76: pwm_put.part.16 (STB_LOCAL)
ffffffff81527019-ffffffff8152702a: pwm_put.part.16.cold.21 (STB_LOCAL)
ffffffff81526a80-ffffffff81526a96: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff815556b8)
Location: drivers/pwm/core.c:983
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81555600-ffffffff8155566e: pwm_put.part.0 (STB_LOCAL)
ffffffff81556027-ffffffff81556038: pwm_put.part.0.cold (STB_LOCAL)
ffffffff81555670-ffffffff81555686: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81576cf8)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81576c40-ffffffff81576cae: pwm_put.part.0 (STB_LOCAL)
ffffffff81577651-ffffffff81577662: pwm_put.part.0.cold (STB_LOCAL)
ffffffff81576cb0-ffffffff81576cc6: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8161b5e8)
Location: drivers/pwm/core.c:1112
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff8161b520-ffffffff8161b591: pwm_put.part.0 (STB_LOCAL)
ffffffff8161c58d-ffffffff8161c59e: pwm_put.part.0.cold (STB_LOCAL)
ffffffff8161b5a0-ffffffff8161b5b6: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81641d58)
Location: drivers/pwm/core.c:1112
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81641c90-ffffffff81641d01: pwm_put.part.0 (STB_LOCAL)
ffffffff81bf6c7a-ffffffff81bf6c8b: pwm_put.part.0.cold (STB_LOCAL)
ffffffff81641d10-ffffffff81641d26: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81624c38)
Location: drivers/pwm/core.c:1082
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81624b70-ffffffff81624be1: pwm_put.part.0 (STB_LOCAL)
ffffffff81be8ade-ffffffff81be8aef: pwm_put.part.0.cold (STB_LOCAL)
ffffffff81624bf0-ffffffff81624c06: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81694f6b)
Location: drivers/pwm/core.c:1042
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff816943c0-ffffffff81694431: pwm_put.part.0 (STB_LOCAL)
ffffffff81ce2c5a-ffffffff81ce2c6b: pwm_put.part.0.cold (STB_LOCAL)
ffffffff81694440-ffffffff81694456: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff817b5bbc)
Location: drivers/pwm/core.c:1096
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff817b5220-ffffffff817b529b: pwm_put.part.0 (STB_LOCAL)
ffffffff81ea9790-ffffffff81ea97a1: pwm_put.part.0.cold (STB_LOCAL)
ffffffff817b52a0-ffffffff817b52c2: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff818cff7c)
Location: drivers/pwm/core.c:1024
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff818cf540-ffffffff818cf5c5: pwm_put.part.0 (STB_LOCAL)
ffffffff818cf5e0-ffffffff818cf602: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81912f03)
Location: drivers/pwm/core.c:967
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff819124e0-ffffffff81912565: pwm_put.part.0 (STB_LOCAL)
ffffffff81912580-ffffffff819125a2: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8195ae43)
Location: drivers/pwm/core.c:951
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_fwnode_pwm_get
  - drivers/pwm/core.c:devm_pwm_get
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff8195a340-ffffffff8195a3b9: pwm_put.part.0 (STB_LOCAL)
ffffffff8195a3d0-ffffffff8195a3f2: pwm_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffff8000106d834c)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffff8000106d81f8-ffff8000106d82d0: pwm_put.part.0 (STB_LOCAL)
ffff8000106d82d0-ffff8000106d8300: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (c0875794)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
c08750b0-c0875140: pwm_put.part.0 (STB_LOCAL)
c0875140-c0875164: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (c00000000084f4b4)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
c00000000084f370-c00000000084f454: pwm_put.part.0 (STB_LOCAL)
c00000000084f460-c00000000084f47c: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffe0004b17e8)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/core.c:of_pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffe0004b16f6-ffffffe0004b1778: pwm_put.part.0 (STB_LOCAL)
ffffffe0004b1778-ffffffe0004b17a4: pwm_put (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156bb08)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff8156ba50-ffffffff8156babe: pwm_put.part.0 (STB_LOCAL)
ffffffff8156c461-ffffffff8156c472: pwm_put.part.0.cold (STB_LOCAL)
ffffffff8156bac0-ffffffff8156bad6: pwm_put (STB_GLOBAL)
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
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff8156aa48)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff8156a990-ffffffff8156a9fe: pwm_put.part.0 (STB_LOCAL)
ffffffff8156b3a1-ffffffff8156b3b2: pwm_put.part.0.cold (STB_LOCAL)
ffffffff8156aa00-ffffffff8156aa16: pwm_put (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void pwm_put(struct pwm_device *pwm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/pwm/core.c (ffffffff81584f48)
Location: drivers/pwm/core.c:984
Inline: True
Inline callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
Direct callers:
  - drivers/pwm/core.c:devm_pwm_release
  - drivers/pwm/core.c:pwm_get
  - drivers/pwm/sysfs.c:export_store
  - drivers/pwm/sysfs.c:pwm_unexport_child
```
**Symbols:**

```
ffffffff81584e90-ffffffff81584efe: pwm_put.part.0 (STB_LOCAL)
ffffffff815858a1-ffffffff815858b2: pwm_put.part.0.cold (STB_LOCAL)
ffffffff81584f00-ffffffff81584f16: pwm_put (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
