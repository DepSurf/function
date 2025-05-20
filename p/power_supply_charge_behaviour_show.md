# Function: <code>power_supply_charge_behaviour_show</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t power_supply_charge_behaviour_show(struct device *dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (0)
Location: drivers/power/supply/power_supply_sysfs.c:497
Inline: False
```
**Symbols:**

```
ffffffff81ef2260-ffffffff81ef227c: power_supply_charge_behaviour_show.cold (STB_LOCAL)
ffffffff81b417c0-ffffffff81b418f0: power_supply_charge_behaviour_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t power_supply_charge_behaviour_show(struct device *dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81cd7db0)
Location: drivers/power/supply/power_supply_sysfs.c:497
Inline: False
```
**Symbols:**

```
ffffffff81cd7db0-ffffffff81cd7f03: power_supply_charge_behaviour_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t power_supply_charge_behaviour_show(struct device *dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81d3fda0)
Location: drivers/power/supply/power_supply_sysfs.c:519
Inline: False
```
**Symbols:**

```
ffffffff81d3fda0-ffffffff81d3fef3: power_supply_charge_behaviour_show (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t power_supply_charge_behaviour_show(struct device *dev, unsigned int available_behaviours, enum power_supply_charge_behaviour current_behaviour, char *buf);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_sysfs.c (ffffffff81df6750)
Location: drivers/power/supply/power_supply_sysfs.c:520
Inline: False
```
**Symbols:**

```
ffffffff81df6750-ffffffff81df68a3: power_supply_charge_behaviour_show (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
