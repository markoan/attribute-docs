# PXUIField

Configures the properties of the input control representing a DAC field in the user interface, or the button representing an action. The attribute is mandatory for all DAC fields that are displayed in the user interface.

```c# title="PXUIField Example"
    [PXDBDecimal(2)]
    [PXUIField(DisplayName = "Documents Total",
              Visibility = PXUIVisibility.SelectorVisible,
              Enabled = false)]
    public virtual decimal? CuryDocsTotal { get; set; }
```

Reference in [help.acumatica.com](<https://help-2022r2.acumatica.com/(W(1))/Help?ScreenId=ShowWiki&pageid=ea7ce94e-4b3e-0f91-df1d-a4ce8023b184>).
