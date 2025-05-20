# Function: <code>sfp_lookup_quirk</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct sfp_quirk *sfp_lookup_quirk(const struct sfp_eeprom_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81888810)
Location: drivers/net/phy/sfp-bus.c:90
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
**Symbols:**

```
ffffffff81888810-ffffffff818888ce: sfp_lookup_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct sfp_quirk *sfp_lookup_quirk(const struct sfp_eeprom_id *id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81896aa0)
Location: drivers/net/phy/sfp-bus.c:105
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
**Symbols:**

```
ffffffff81896aa0-ffffffff81896b5e: sfp_lookup_quirk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878f93)
Location: drivers/net/phy/sfp-bus.c:105
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81909b36)
Location: drivers/net/phy/sfp-bus.c:105
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d221)
Location: drivers/net/phy/sfp-bus.c:111
Inline: True
Inline callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
