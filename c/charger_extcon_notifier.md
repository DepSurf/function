# Function: <code>charger_extcon_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff81680ce0)
Location: drivers/power/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81680ce0-ffffffff81680d43: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/charger-manager.c (ffffffff816e1ad0)
Location: drivers/power/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff816e1ad0-ffffffff816e1b33: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81711f40)
Location: drivers/power/supply/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff81711f40-ffffffff81711fa3: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8172a310)
Location: drivers/power/supply/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff8172a310-ffffffff8172a373: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8179baa0)
Location: drivers/power/supply/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff8179baa0-ffffffff8179bb03: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff817e2ff0)
Location: drivers/power/supply/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff817e2ff0-ffffffff817e3053: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8180e840)
Location: drivers/power/supply/charger-manager.c:1161
Inline: False
```
**Symbols:**

```
ffffffff8180e840-ffffffff8180e8a3: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81850430)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffffffff81850430-ffffffff81850493: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81882230)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffffffff81882230-ffffffff81882293: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81951040)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffffffff81951040-ffffffff819510a6: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff819567a0)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff819567f0-ffffffff81956819: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff8193a3b9)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff8193a440-ffffffff8193a469: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff819deb58)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff819debe0-ffffffff819dec09: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81b435d2)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81b43660-ffffffff81b43693: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81cda0cb)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81cda1b0-ffffffff81cda1e3: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81d42325)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81d42430-ffffffff81d42463: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81df8cd5)
Location: drivers/power/supply/charger-manager.c:945
Inline: True
Inline callers:
  - drivers/power/supply/charger-manager.c:charger_manager_register_extcon
```
**Symbols:**

```
ffffffff81df8de0-ffffffff81df8e13: charger_extcon_notifier (STB_LOCAL)
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
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffff800010aceac0)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffff800010aceac0-ffff800010aceb74: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c0baf124)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
c0baf124-c0baf1a8: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (c000000000bb1c70)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
c000000000bb1c70-c000000000bb1d64: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffe0006cb716)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffffffe0006cb716-ffffffe0006cb7a0: charger_extcon_notifier (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff818776e0)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffffffff818776e0-ffffffff81877743: charger_extcon_notifier (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int charger_extcon_notifier(struct notifier_block *self, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/charger-manager.c (ffffffff81893080)
Location: drivers/power/supply/charger-manager.c:1159
Inline: False
```
**Symbols:**

```
ffffffff81893080-ffffffff818930e3: charger_extcon_notifier (STB_LOCAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
