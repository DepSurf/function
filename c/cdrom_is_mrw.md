# Function: <code>cdrom_is_mrw</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff815fe280)
Location: drivers/cdrom/cdrom.c:442
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff815fe280-ffffffff815fe337: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8165e1d0)
Location: drivers/cdrom/cdrom.c:442
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff8165e1d0-ffffffff8165e281: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8168bfc0)
Location: drivers/cdrom/cdrom.c:442
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff8168bfc0-ffffffff8168c071: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff816a10a0)
Location: drivers/cdrom/cdrom.c:443
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff816a10a0-ffffffff816a1151: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8170c2d0)
Location: drivers/cdrom/cdrom.c:443
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff8170c2d0-ffffffff8170c387: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8174b650)
Location: drivers/cdrom/cdrom.c:443
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff8174b650-ffffffff8174b707: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff8176f870)
Location: drivers/cdrom/cdrom.c:444
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff8176f870-ffffffff8176f927: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ad700)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff817ad700-ffffffff817ad7b4: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817dd9e0)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff817dd9e0-ffffffff817dda94: cdrom_is_mrw (STB_LOCAL)
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
In drivers/cdrom/cdrom.c (ffffffff818af7c5)
Location: drivers/cdrom/cdrom.c:445
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff818be545)
Location: drivers/cdrom/cdrom.c:445
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff818a0ff5)
Location: drivers/cdrom/cdrom.c:445
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81935845)
Location: drivers/cdrom/cdrom.c:445
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81a8e4fb)
Location: drivers/cdrom/cdrom.c:441
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81c0f9bb)
Location: drivers/cdrom/cdrom.c:441
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81c752ab)
Location: drivers/cdrom/cdrom.c:442
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
In drivers/cdrom/cdrom.c (ffffffff81d29cab)
Location: drivers/cdrom/cdrom.c:442
Inline: True
Inline callers:
  - drivers/cdrom/cdrom.c:cdrom_open_write
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
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffff800010a0afc8)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffff800010a0afc8-ffff800010a0b0ac: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c0ae2be0)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
c0ae2be0-c0ae2cc0: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (c000000000ac0c70)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
c000000000ac0c70-c000000000ac0d94: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffe000631afa)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffe000631afa-ffffffe000631ba6: cdrom_is_mrw (STB_LOCAL)
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
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81795dc0)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81795dc0-ffffffff81795e74: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff81787a90)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff81787a90-ffffffff81787b44: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817d2860)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff817d2860-ffffffff817d2914: cdrom_is_mrw (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cdrom_is_mrw(struct cdrom_device_info *cdi, int *write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/cdrom/cdrom.c (ffffffff817ecb00)
Location: drivers/cdrom/cdrom.c:445
Inline: False
Direct callers:
  - drivers/cdrom/cdrom.c:cdrom_open
```
**Symbols:**

```
ffffffff817ecb00-ffffffff817ecbb4: cdrom_is_mrw (STB_LOCAL)
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
