# Function: <code>elants_i2c_do_update_firmware</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81700a15)
Location: drivers/input/touchscreen/elants_i2c.c:620
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8171627b)
Location: drivers/input/touchscreen/elants_i2c.c:620
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff8178747b)
Location: drivers/input/touchscreen/elants_i2c.c:621
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817c8529)
Location: drivers/input/touchscreen/elants_i2c.c:620
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
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
In drivers/input/touchscreen/elants_i2c.c (ffffffff817efbc9)
Location: drivers/input/touchscreen/elants_i2c.c:621
Inline: True
Inline callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81830e4b)
Location: drivers/input/touchscreen/elants_i2c.c:616
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81830e4b-ffffffff818311b5: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8186277b)
Location: drivers/input/touchscreen/elants_i2c.c:616
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8186277b-ffffffff81862ae5: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81935ec1)
Location: drivers/input/touchscreen/elants_i2c.c:661
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81935ec1-ffffffff81936241: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81c23b03)
Location: drivers/input/touchscreen/elants_i2c.c:669
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81c23b03-ffffffff81c23e83: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81c15ac9)
Location: drivers/input/touchscreen/elants_i2c.c:739
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81c15ac9-ffffffff81c15ee1: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d2447f)
Location: drivers/input/touchscreen/elants_i2c.c:783
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81d2447f-ffffffff81d248e4: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81ef02dd)
Location: drivers/input/touchscreen/elants_i2c.c:783
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81ef02dd-ffffffff81ef0754: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81cb6030)
Location: drivers/input/touchscreen/elants_i2c.c:783
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81cb6030-ffffffff81cb66cf: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81d1d6c0)
Location: drivers/input/touchscreen/elants_i2c.c:783
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81d1d6c0-ffffffff81d1dd70: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81dd33c0)
Location: drivers/input/touchscreen/elants_i2c.c:783
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:elants_i2c_fw_update
```
**Symbols:**

```
ffffffff81dd33c0-ffffffff81dd3a70: elants_i2c_do_update_firmware (STB_LOCAL)
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
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff8185690b)
Location: drivers/input/touchscreen/elants_i2c.c:616
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff8185690b-ffffffff81856c75: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int elants_i2c_do_update_firmware(struct i2c_client *client, const struct firmware *fw, bool force);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/touchscreen/elants_i2c.c (ffffffff81871a3b)
Location: drivers/input/touchscreen/elants_i2c.c:616
Inline: False
Direct callers:
  - drivers/input/touchscreen/elants_i2c.c:write_update_fw
```
**Symbols:**

```
ffffffff81871a3b-ffffffff81871da5: elants_i2c_do_update_firmware (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
