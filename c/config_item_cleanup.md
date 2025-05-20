# Function: <code>config_item_cleanup</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff812e1c80)
Location: fs/configfs/item.c:149
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
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
In fs/configfs/item.c (ffffffff81306655)
Location: fs/configfs/item.c:149
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/item.c (ffffffff81334645)
Location: fs/configfs/item.c:149
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/item.c (ffffffff8134b965)
Location: fs/configfs/item.c:133
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/item.c (ffffffff81374325)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/item.c (ffffffff8138c5a5)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813d7990)
Location: fs/configfs/item.c:119
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffff813d7990-ffffffff813d7a7e: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813e9630)
Location: fs/configfs/item.c:119
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffff813e9630-ffffffff813e971e: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813f0190)
Location: fs/configfs/item.c:117
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffff813f0190-ffffffff813f027e: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81442080)
Location: fs/configfs/item.c:117
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffff81442080-ffffffff8144216b: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff814bddb0)
Location: fs/configfs/item.c:117
Inline: False
```
**Symbols:**

```
ffffffff814bddb0-ffffffff814bde4f: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81555b30)
Location: fs/configfs/item.c:117
Inline: False
```
**Symbols:**

```
ffffffff81555b30-ffffffff81555bcf: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff8158d8d0)
Location: fs/configfs/item.c:117
Inline: False
```
**Symbols:**

```
ffffffff8158d8d0-ffffffff8158d96f: config_item_cleanup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff815c6610)
Location: fs/configfs/item.c:117
Inline: False
```
**Symbols:**

```
ffffffff815c6610-ffffffff815c66af: config_item_cleanup (STB_LOCAL)
```
</details>
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
In fs/configfs/item.c (ffff80001045e104)
Location: fs/configfs/item.c:119
Inline: True
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
In fs/configfs/item.c (c061eb94)
Location: fs/configfs/item.c:119
Inline: True
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
In fs/configfs/item.c (c000000000579ce0)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void config_item_cleanup(struct config_item *item);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffe0002eddf8)
Location: fs/configfs/item.c:119
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
**Symbols:**

```
ffffffe0002eddf8-ffffffe0002eded4: config_item_cleanup (STB_LOCAL)
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
In fs/configfs/item.c (ffffffff81384b85)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81375615)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81382655)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
In fs/configfs/item.c (ffffffff81396175)
Location: fs/configfs/item.c:119
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_release
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
</ul>
