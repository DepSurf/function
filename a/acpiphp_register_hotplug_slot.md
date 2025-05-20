# Function: <code>acpiphp_register_hotplug_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81451ce0)
Location: drivers/pci/hotplug/acpiphp_core.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81451ce0-ffffffff81451e74: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8149e4c0)
Location: drivers/pci/hotplug/acpiphp_core.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8149e4c0-ffffffff8149e643: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814c00f0)
Location: drivers/pci/hotplug/acpiphp_core.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff814c00f0-ffffffff814c0273: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff814ca840)
Location: drivers/pci/hotplug/acpiphp_core.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff814ca840-ffffffff814ca9c3: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff8150ae10)
Location: drivers/pci/hotplug/acpiphp_core.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8150ae10-ffffffff8150af93: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:272
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8153fbdc-ffffffff8153fc0f: acpiphp_register_hotplug_slot.cold.4 (STB_LOCAL)
ffffffff8153fa80-ffffffff8153fbdc: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81556f04-ffffffff81556f34: acpiphp_register_hotplug_slot.cold.2 (STB_LOCAL)
ffffffff81556e30-ffffffff81556f04: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81586f3c-ffffffff81586f6d: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff81586e70-ffffffff81586f3c: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff815a890c-ffffffff815a893d: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff815a8840-ffffffff815a890c: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff816515cc-ffffffff816515fd: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff81651500-ffffffff816515cc: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81bfdac5-ffffffff81bfdaf6: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff81673f30-ffffffff81673ffc: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81bef9ce-ffffffff81bef9ff: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff81656460-ffffffff8165652c: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81cead69-ffffffff81cead9a: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff816c8430-ffffffff816c84fc: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81eb1dab-ffffffff81eb1ddb: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff817ee5a0-ffffffff817ee69e: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819165b0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff819165b0-ffffffff819166d2: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff81959ba0)
Location: drivers/pci/hotplug/acpiphp_core.c:257
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff81959ba0-ffffffff81959cc2: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffffffff819a3110)
Location: drivers/pci/hotplug/acpiphp_core.c:256
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff819a3110-ffffffff819a3261: acpiphp_register_hotplug_slot (STB_GLOBAL)
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
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (ffff8000107119a0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffff8000107119a0-ffff800010711ab8: acpiphp_register_hotplug_slot (STB_GLOBAL)
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
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8159c11c-ffffffff8159c14d: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff8159c050-ffffffff8159c11c: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8158b2ac-ffffffff8158b2dd: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff8158b1e0-ffffffff8158b2ac: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff8159c65c-ffffffff8159c68d: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff8159c590-ffffffff8159c65c: acpiphp_register_hotplug_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int acpiphp_register_hotplug_slot(struct acpiphp_slot *acpiphp_slot, unsigned int sun);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/hotplug/acpiphp_core.c (0)
Location: drivers/pci/hotplug/acpiphp_core.c:258
Inline: False
Direct callers:
  - drivers/pci/hotplug/acpiphp_glue.c:acpiphp_add_context
```
**Symbols:**

```
ffffffff815b6a8c-ffffffff815b6abd: acpiphp_register_hotplug_slot.cold (STB_LOCAL)
ffffffff815b69c0-ffffffff815b6a8c: acpiphp_register_hotplug_slot (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
