# Function: <code>pci_bus_find_capability</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814352b0)
Location: drivers/pci/pci.c:262
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
```
**Symbols:**

```
ffffffff814352b0-ffffffff81435339: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81480c10)
Location: drivers/pci/pci.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81480c10-ffffffff81480c99: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814a22d0)
Location: drivers/pci/pci.c:283
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff814a22d0-ffffffff814a2359: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814ac070)
Location: drivers/pci/pci.c:285
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff814ac070-ffffffff814ac0f9: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff814eb140)
Location: drivers/pci/pci.c:286
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff814eb140-ffffffff814eb1c9: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8151a700)
Location: drivers/pci/pci.c:298
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8151a700-ffffffff8151a78b: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81530460)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81530460-ffffffff815304eb: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8155fc40)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8155fc40-ffffffff8155fccd: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81580d70)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81580d70-ffffffff81580dfd: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81625d90)
Location: drivers/pci/pci.c:496
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81625d90-ffffffff81625e40: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8164bbb0)
Location: drivers/pci/pci.c:505
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8164bbb0-ffffffff8164bc60: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8162e780)
Location: drivers/pci/pci.c:505
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8162e780-ffffffff8162e830: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8169dbe0)
Location: drivers/pci/pci.c:515
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8169dbe0-ffffffff8169dc90: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff817bdfb0)
Location: drivers/pci/pci.c:532
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff817bdfb0-ffffffff817be07c: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff818da270)
Location: drivers/pci/pci.c:516
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff818da270-ffffffff818da33c: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8191d5b0)
Location: drivers/pci/pci.c:531
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8191d5b0-ffffffff8191d67c: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u8 pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff819659e0)
Location: drivers/pci/pci.c:531
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff819659e0-ffffffff81965aac: pci_bus_find_capability (STB_GLOBAL)
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
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffff8000106e3ba8)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffff8000106e3ba8-ffff8000106e3c54: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c087fa68)
Location: drivers/pci/pci.c:464
Inline: False
```
**Symbols:**

```
c087fa68-c087fb14: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (c00000000085de00)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - arch/powerpc/kernel/pci-common.c:early_find_capability
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
c00000000085de00-c00000000085decc: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffe0004bb052)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffe0004bb052-ffffffe0004bb0d2: pci_bus_find_capability (STB_GLOBAL)
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
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81575290)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81575290-ffffffff8157531d: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff815639f0)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff815639f0-ffffffff81563a7d: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff81574ac0)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff81574ac0-ffffffff81574b4d: pci_bus_find_capability (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int pci_bus_find_capability(struct pci_bus *bus, unsigned int devfn, int cap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/pci.c (ffffffff8158f090)
Location: drivers/pci/pci.c:464
Inline: False
Direct callers:
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_off
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_led_on
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_clear_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_ext
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_check_and_clear_ins
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_hs_csr
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_set_attention_status
  - drivers/pci/hotplug/cpci_hotplug_pci.c:cpci_get_attention_status
```
**Symbols:**

```
ffffffff8158f090-ffffffff8158f11d: pci_bus_find_capability (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>u8</code>
</li>
</ul>
</details>
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
