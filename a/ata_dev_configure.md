# Function: <code>ata_dev_configure</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff815cc9f0)
Location: drivers/ata/libata-core.c:2163
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff815cc9f0-ffffffff815cda83: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81625200)
Location: drivers/ata/libata-core.c:2337
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81625200-ffffffff8162666c: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81655da0)
Location: drivers/ata/libata-core.c:2379
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81655da0-ffffffff816572cb: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff8166a320)
Location: drivers/ata/libata-core.c:2455
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8166a320-ffffffff8166bad3: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff816d3970)
Location: drivers/ata/libata-core.c:2456
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff816d3970-ffffffff816d5126: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2447
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff817134da-ffffffff81713a7a: ata_dev_configure.cold.58 (STB_LOCAL)
ffffffff81710080-ffffffff81710f85: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2447
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff81735989-ffffffff81735f29: ata_dev_configure.cold.59 (STB_LOCAL)
ffffffff81732530-ffffffff81733434: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff817714a2-ffffffff81771a4e: ata_dev_configure.cold (STB_LOCAL)
ffffffff8176dfe0-ffffffff8176ee21: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8179547d-ffffffff81795a29: ata_dev_configure.cold (STB_LOCAL)
ffffffff81792050-ffffffff81792e91: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2379
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81859960-ffffffff81859db6: ata_dev_configure.cold (STB_LOCAL)
ffffffff81857090-ffffffff81857a79: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2379
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c17973-ffffffff81c17dc9: ata_dev_configure.cold (STB_LOCAL)
ffffffff81867310-ffffffff81867cf9: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2379
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c095fe-ffffffff81c09acc: ata_dev_configure.cold (STB_LOCAL)
ffffffff818499b0-ffffffff8184a568: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2494
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81d0de4b-ffffffff81d0e27e: ata_dev_configure.cold (STB_LOCAL)
ffffffff818d6a10-ffffffff818d775e: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2532
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81ed6dda-ffffffff81ed7139: ata_dev_configure.cold (STB_LOCAL)
ffffffff81a27760-ffffffff81a2864a: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81ba9d40)
Location: drivers/ata/libata-core.c:2533
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81ba9d40-ffffffff81baaf53: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c00da0)
Location: drivers/ata/libata-core.c:2724
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c00da0-ffffffff81c02044: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffff81c56e10)
Location: drivers/ata/libata-core.c:2859
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffffffff81c56e10-ffffffff81c580d8: ata_dev_configure (STB_GLOBAL)
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
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffff80001099c0d0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
ffff80001099c0d0-ffff80001099d1f4: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c0a6bf54)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
c0a6bf54-c0a6d708: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (c000000000a5fae0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_revalidate_and_attach
```
**Symbols:**

```
c000000000a5fae0-c000000000a60e98: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/ata/libata-core.c (ffffffe0005fc46a)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffe0005fc46a-ffffffe0005fd532: ata_dev_configure (STB_GLOBAL)
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
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8175a58d-ffffffff8175ab40: ata_dev_configure.cold (STB_LOCAL)
ffffffff81757190-ffffffff81757fa4: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8173a42d-ffffffff8173a9e0: ata_dev_configure.cold (STB_LOCAL)
ffffffff81737030-ffffffff81737e44: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff8178a2fd-ffffffff8178a8a9: ata_dev_configure.cold (STB_LOCAL)
ffffffff81786ed0-ffffffff81787d11: ata_dev_configure (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ata_dev_configure(struct ata_device *dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/ata/libata-core.c (0)
Location: drivers/ata/libata-core.c:2431
Inline: False
Direct callers:
  - drivers/ata/libata-core.c:ata_dev_revalidate
  - drivers/ata/libata-core.c:ata_bus_probe
  - drivers/ata/libata-eh.c:ata_eh_recover
```
**Symbols:**

```
ffffffff817a414d-ffffffff817a46f9: ata_dev_configure.cold (STB_LOCAL)
ffffffff817a0d20-ffffffff817a1b61: ata_dev_configure (STB_GLOBAL)
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
