# Function: <code>config_item_release</code>

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
Location: fs/configfs/item.c:167
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81306640)
Location: fs/configfs/item.c:167
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81306640-ffffffff81306701: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81334640)
Location: fs/configfs/item.c:167
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81334640-ffffffff8133470e: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff8134b960)
Location: fs/configfs/item.c:151
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff8134b960-ffffffff8134ba2e: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81374320)
Location: fs/configfs/item.c:137
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81374320-ffffffff813743e5: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff8138c5a0)
Location: fs/configfs/item.c:137
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff8138c5a0-ffffffff8138c665: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813d7a5c)
Location: fs/configfs/item.c:137
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff813e96fc)
Location: fs/configfs/item.c:137
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/item.c (ffffffff813f025c)
Location: fs/configfs/item.c:135
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/item.c (ffffffff81442149)
Location: fs/configfs/item.c:135
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
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
In fs/configfs/item.c (ffffffff814bdd7a)
Location: fs/configfs/item.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81555aea)
Location: fs/configfs/item.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff8158d88a)
Location: fs/configfs/item.c:135
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff815c65ca)
Location: fs/configfs/item.c:135
Inline: True
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
Location: fs/configfs/item.c:137
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
Location: fs/configfs/item.c:137
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
Location: fs/configfs/item.c:137
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_put
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
In fs/configfs/item.c (ffffffe0002ede96)
Location: fs/configfs/item.c:137
Inline: True
Inline callers:
  - fs/configfs/item.c:config_item_cleanup
  - fs/configfs/item.c:config_item_cleanup
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
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81384b80)
Location: fs/configfs/item.c:137
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81384b80-ffffffff81384c45: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81375610)
Location: fs/configfs/item.c:137
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81375610-ffffffff813756d5: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81382650)
Location: fs/configfs/item.c:137
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81382650-ffffffff81382715: config_item_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void config_item_release(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/configfs/item.c (ffffffff81396170)
Location: fs/configfs/item.c:137
Inline: False
Direct callers:
  - fs/configfs/item.c:config_item_release
  - fs/configfs/item.c:config_item_release
```
**Symbols:**

```
ffffffff81396170-ffffffff81396235: config_item_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
