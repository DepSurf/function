# Function: <code>ata_down_xfermask_limit</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815ca8c0)
Location: drivers/ata/libata-core.c:3130
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff815ca8c0-ffffffff815cab6a: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81623100)
Location: drivers/ata/libata-core.c:3305
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81623100-ffffffff816233a9: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81653c80)
Location: drivers/ata/libata-core.c:3347
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81653c80-ffffffff81653f29: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816683b0)
Location: drivers/ata/libata-core.c:3424
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816683b0-ffffffff8166863e: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d1a20)
Location: drivers/ata/libata-core.c:3432
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff816d1a20-ffffffff816d1cb4: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3426
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81713102-ffffffff817131b4: ata_down_xfermask_limit.cold.51 (STB_LOCAL)
ffffffff8170e1e0-ffffffff8170e3d4: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3426
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff817355b2-ffffffff81735664: ata_down_xfermask_limit.cold.52 (STB_LOCAL)
ffffffff81730650-ffffffff8173085d: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81771000-ffffffff817710b6: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff8176bdc0-ffffffff8176bfbf: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81794ffe-ffffffff817950b4: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff8178fe30-ffffffff8179002f: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3120
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81859457-ffffffff8185950d: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81854890-ffffffff81854a93: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3120
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81c1746a-ffffffff81c17520: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81864b60-ffffffff81864d63: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3120
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81c09097-ffffffff81c0914d: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff818475f0-ffffffff81847806: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3171
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81d0d928-ffffffff81d0d9c3: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff818d43d0-ffffffff818d4729: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3202
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff81ed68ee-ffffffff81ed69a1: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81a24bf0-ffffffff81a24f27: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3204
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff8209c5d4-ffffffff8209c637: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81ba6cb0-ffffffff81ba7030: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3397
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
```
**Symbols:**

```
ffffffff8211d504-ffffffff8211d592: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81bfd890-ffffffff81bfdbf1: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3394
Inline: False
Direct callers:
  - drivers/ata/libata-eh.c:ata_do_eh
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_speed_down
  - drivers/ata/libata-eh.c:ata_eh_detach_dev
  - drivers/ata/libata-eh.c:ata_eh_unload
```
**Symbols:**

```
ffffffff821fb53c-ffffffff821fb5ca: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81c53650-ffffffff81c539aa: ata_down_xfermask_limit (STB_GLOBAL)
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
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff800010999a30)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffff800010999a30-ffff800010999c80: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a69a0c)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
c0a69a0c-c0a69c40: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5cb70)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
c000000000a5cb70-c000000000a5ce70: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fa42a)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffe0005fa42a-ffffffe0005fa6b2: ata_down_xfermask_limit (STB_GLOBAL)
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
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff8175a10e-ffffffff8175a1c4: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81754fa0-ffffffff8175519f: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81739fae-ffffffff8173a064: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81734e40-ffffffff8173503f: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff81789e7e-ffffffff81789f34: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff81784cb0-ffffffff81784eaf: ata_down_xfermask_limit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_down_xfermask_limit(struct ata_device *dev, unsigned int sel);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:3410
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
  - drivers/ata/libata-eh.c:ata_eh_link_autopsy
```
**Symbols:**

```
ffffffff817a3cce-ffffffff817a3d84: ata_down_xfermask_limit.cold (STB_LOCAL)
ffffffff8179eaa0-ffffffff8179ec9f: ata_down_xfermask_limit (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
