# Function: <code>nvm_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815438fc)
Location: drivers/lightnvm/core.c:488
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815958ac)
Location: drivers/lightnvm/core.c:610
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815c3403)
Location: drivers/lightnvm/core.c:729
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff815d9594)
Location: drivers/lightnvm/core.c:1033
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816402fa)
Location: drivers/lightnvm/core.c:1039
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff8167a5b3)
Location: drivers/lightnvm/core.c:893
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81699ee3)
Location: drivers/lightnvm/core.c:1105
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816d2a73)
Location: drivers/lightnvm/core.c:1108
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816f6953)
Location: drivers/lightnvm/core.c:1138
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int nvm_init(struct nvm_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1137
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff817af7a0-ffffffff817af884: nvm_init (STB_LOCAL)
ffffffff817b0669-ffffffff817b06dd: nvm_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int nvm_init(struct nvm_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1132
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff817c4320-ffffffff817c4404: nvm_init (STB_LOCAL)
ffffffff81c0d91d-ffffffff81c0d991: nvm_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int nvm_init(struct nvm_dev *dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/lightnvm/core.c (0)
Location: drivers/lightnvm/core.c:1132
Inline: False
Direct callers:
  - drivers/lightnvm/core.c:nvm_register
```
**Symbols:**

```
ffffffff817a8220-ffffffff817a842d: nvm_init (STB_LOCAL)
ffffffff81bffe25-ffffffff81bffea5: nvm_init.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffff8000108e06c4)
Location: drivers/lightnvm/core.c:1138
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c09cf270)
Location: drivers/lightnvm/core.c:1138
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (c0000000009740e8)
Location: drivers/lightnvm/core.c:1138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffe000576050)
Location: drivers/lightnvm/core.c:1138
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816bc143)
Location: drivers/lightnvm/core.c:1138
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff816ea613)
Location: drivers/lightnvm/core.c:1138
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/lightnvm/core.c (ffffffff81704e53)
Location: drivers/lightnvm/core.c:1138
Inline: True
Inline callers:
  - drivers/lightnvm/core.c:nvm_register
```
</details>
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
</ul>
