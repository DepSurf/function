# Function: <code>sfp_match</code>

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
bool sfp_match(const char *qs, const char *str, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff818887b0)
Location: drivers/net/phy/sfp-bus.c:81
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_lookup_quirk
  - drivers/net/phy/sfp-bus.c:sfp_lookup_quirk
  - drivers/net/phy/sfp-bus.c:sfp_lookup_quirk
```
**Symbols:**

```
ffffffff818887b0-ffffffff81888805: sfp_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool sfp_match(const char *qs, const char *str, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81896a40)
Location: drivers/net/phy/sfp-bus.c:96
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_lookup_quirk
  - drivers/net/phy/sfp-bus.c:sfp_lookup_quirk
  - drivers/net/phy/sfp-bus.c:sfp_lookup_quirk
```
**Symbols:**

```
ffffffff81896a40-ffffffff81896a95: sfp_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool sfp_match(const char *qs, const char *str, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81878f00)
Location: drivers/net/phy/sfp-bus.c:96
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
**Symbols:**

```
ffffffff81878f00-ffffffff81878f55: sfp_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool sfp_match(const char *qs, const char *str, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81909a90)
Location: drivers/net/phy/sfp-bus.c:96
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
**Symbols:**

```
ffffffff81909a90-ffffffff81909ae5: sfp_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool sfp_match(const char *qs, const char *str, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/sfp-bus.c (ffffffff81a5d170)
Location: drivers/net/phy/sfp-bus.c:102
Inline: False
Direct callers:
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
  - drivers/net/phy/sfp-bus.c:sfp_module_insert
```
**Symbols:**

```
ffffffff81a5d170-ffffffff81a5d1e0: sfp_match (STB_LOCAL)
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
