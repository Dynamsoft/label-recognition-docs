---
layout: default-layout
title: Dynamsoft Label Recognizer iOS API Reference - iDLRLineSpecification Struct
description: This page shows the iDLRLineSpecification Struct of Dynamsoft Label Recognizer for iOS SDK.
keywords: iDLRLineSpecification, iOS
needAutoGenerateSidebar: true
needGenerateH3Content: true
---


# iDLRLineSpecification
Stores the settings of text line.

## Attributes
  
| Attribute | Type |
|---------- | ---- |
| [`grayscaleEnhancementModes`](#grayscaleenhancementmodes) | *NSArray\** | 
| [`binarizationModes`](#binarizationmodes) | *NSArray\** |

### grayscaleEnhancementModes
Sets the mode and priority for grayscale image preprocessing algorithms.

```objc
NSArray * grayscaleEnhancementModes
```

- **Value range**  
   Each array item can be any one of the [`EnumGrayscaleEnhancementMode`]({{ site.enumerations }}parameter-mode-enums.html#grayscaleenhancementmode) Enumeration items.  
     
- **Default value**  
   `[EnumGrayscaleEnhancementModeGeneral, EnumGrayscaleEnhancementModeSkip, EnumGrayscaleEnhancementModeSkip, EnumGrayscaleEnhancementModeSkip, EnumGrayscaleEnhancementModeSkip, EnumGrayscaleEnhancementModeSkip, EnumGrayscaleEnhancementModeSkip, EnumGrayscaleEnhancementModeSkip]`  
     
- **Remarks**  
   The array index represents the priority of the item. The smaller index is, the higher priority is.


### binarizationModes
Sets the mode and priority for binarization.

```objc
NSArray * binarizationModes
```

- **Value range**   
    Each array item can be any one of the [`EnumBinarizationMode`]({{ site.enumerations }}parameter-mode-enums.html#binarizationmode) Enumeration items.
      
- **Default value**   
    `[EnumBinarizationModeLocalBlock, EnumBinarizationModeSkip, EnumBinarizationModeSkip, EnumBinarizationModeSkip, EnumBinarizationModeSkip, EnumBinarizationModeSkip, EnumBinarizationModeSkip, EnumBinarizationModeSkip]`
    
- **Remarks**   
    The array index represents the priority of the item. The smaller index is, the higher priority is.