# Function: <code>devm_rtc_nvmem_register</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81c24611-ffffffff81c2462d: devm_rtc_nvmem_register.cold (STB_LOCAL)
ffffffff819421d0-ffffffff81942219: devm_rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81c166ce-ffffffff81c166ea: devm_rtc_nvmem_register.cold (STB_LOCAL)
ffffffff81925a00-ffffffff81925a49: devm_rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81d25173-ffffffff81d2518f: devm_rtc_nvmem_register.cold (STB_LOCAL)
ffffffff819c8970-ffffffff819c89b9: devm_rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/rtc/nvmem.c (0)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81ef0f58-ffffffff81ef0f74: devm_rtc_nvmem_register.cold (STB_LOCAL)
ffffffff81b298f0-ffffffff81b29940: devm_rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff81cbd4f0)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81cbd4f0-ffffffff81cbd550: devm_rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff81d24e00)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81d24e00-ffffffff81d24e60: devm_rtc_nvmem_register (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devm_rtc_nvmem_register(struct rtc_device *rtc, struct nvmem_config *nvmem_config);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/rtc/nvmem.c (ffffffff81ddab60)
Location: drivers/rtc/nvmem.c:13
Inline: False
Direct callers:
  - drivers/rtc/rtc-cmos.c:cmos_do_probe
```
**Symbols:**

```
ffffffff81ddab60-ffffffff81ddabc4: devm_rtc_nvmem_register (STB_GLOBAL)
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
