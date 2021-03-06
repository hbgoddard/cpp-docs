---
title: "Compiler Errors C3000 Through C3099 | Microsoft Docs"
ms.custom: ""
ms.date: "04/21/2017"
ms.reviewer: ""
ms.suite: ""
ms.technology:  
  - "cpp-tools"
ms.tgt_pltfrm: ""
ms.topic: "error-reference"
f1_keywords: 
  - "C3051"
  - "C3061"
  - "C3064"
  - "C3067"
  - "C3074"
  - "C3078"
  - "C3079"
  - "C3081"
  - "C3082"
  - "C3086"
  - "C3088"
  - "C3089"
  - "C3090"
  - "C3091"
  - "C3092"
  - "C3093"
  - "C3098"
helpviewer_keywords: 
  - "C3051"
  - "C3061"
  - "C3064"
  - "C3067"
  - "C3074"
  - "C3078"
  - "C3079"
  - "C3081"
  - "C3082"
  - "C3086"
  - "C3088"
  - "C3089"
  - "C3090"
  - "C3091"
  - "C3092"
  - "C3093"
  - "C3098"
dev_langs: 
  - "C++"
ms.assetid: 01b7b9cb-b351-4b5a-8cb0-1fcddb08d2ab
caps.latest.revision: 1
author: "corob-msft"
ms.author: "corob"
manager: "ghogen"
translation.priority.ht: 
  - "cs-cz"
  - "de-de"
  - "es-es"
  - "fr-fr"
  - "it-it"
  - "ja-jp"
  - "ko-kr"
  - "pl-pl"
  - "pt-br"
  - "ru-ru"
  - "tr-tr"
  - "zh-cn"
  - "zh-tw"
---
# Compiler Errors C3000 Through C3099
The articles in this part of the documentation contain information about a subsection of the Visual C++ compiler errors. You can access the information here or, in the **Output** window in Visual Studio, you can select an error number and then choose the F1 key.  
  
> [!NOTE]
>  Not every [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] error is documented in MSDN. In many cases, the diagnostic message provides all of the information that's available. If you think an error message needs additional explanation, you can let us know. You can use the feedback form on this page, or go to the menu bar in Visual Studio and choose **Help**, **Report a Bug**, or you can submit a suggestion or bug report on [Microsoft Connect](http://connect.microsoft.com/VisualStudio).  
  
 You may find additional assistance for errors and warnings on the MSDN public forums. The [Visual C++ Language](http://go.microsoft.com/fwlink/?LinkId=158195) forum is for questions and discussions about the [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] language syntax and compiler. The [Visual C++ General](http://go.microsoft.com/fwlink/?LinkId=158194) forum is for questions about [!INCLUDE[vcprvc](../../build/includes/vcprvc_md.md)] that are not discussed in other forums. You may also find help about errors and warnings on [Stack Overflow](http://stackoverflow.com/).  
  
|Error|Message|  
|-----------|-------------|  
|Compiler Error C3000|Obsolete.|  
|[Compiler Error C3001](compiler-error-c3001.md)|'*message*': expected an OpenMP directive name|  
|[Compiler Error C3002](compiler-error-c3002.md)|'*name1* *name2*': multiple OpenMP directive names|  
|[Compiler Error C3003](compiler-error-c3003.md)|'*directive*': OpenMP directive name not allowed after directive clauses|  
|[Compiler Error C3004](compiler-error-c3004.md)|'*clause*': clause not valid on OpenMP '*directive*' directive|  
|[Compiler Error C3005](compiler-error-c3005.md)|'*message*': unexpected token encountered on OpenMP '*directive*' directive|  
|[Compiler Error C3006](compiler-error-c3006.md)|'*clause*': clause on OpenMP '*directive*' directive is missing an expected argument|  
|[Compiler Error C3007](compiler-error-c3007.md)|'*clause*': clause on OpenMP '*directive*' directive does not take an argument|  
|[Compiler Error C3008](compiler-error-c3008.md)|'*argument*': argument is missing closing ')' on OpenMP '*directive*' directive|  
|[Compiler Error C3009](compiler-error-c3009.md)|'*label*': jump into OpenMP structured block not allowed|  
|[Compiler Error C3010](compiler-error-c3010.md)|'*label*': jump out of OpenMP structured block not allowed|  
|[Compiler Error C3011](compiler-error-c3011.md)|inline assembly not allowed directly within a parallel region|  
|[Compiler Error C3012](compiler-error-c3012.md)|'*function*': intrinsic function not allowed directly within a parallel region|  
|[Compiler Error C3013](compiler-error-c3013.md)|'*clause*': clause may only appear once on OpenMP '*directive*' directive|  
|[Compiler Error C3014](compiler-error-c3014.md)|expected a for loop following OpenMP '*directive*' directive|  
|[Compiler Error C3015](compiler-error-c3015.md)|initialization in OpenMP 'for' statement has improper form|  
|[Compiler Error C3016](compiler-error-c3016.md)|'*identifier*': index variable in OpenMP 'for' statement must have signed integral type|  
|[Compiler Error C3017](compiler-error-c3017.md)|termination test in OpenMP 'for' statement has improper form|  
|[Compiler Error C3018](compiler-error-c3018.md)|'*identifier*': OpenMP 'for' test or increment must use index variable '*variable*'|  
|[Compiler Error C3019](compiler-error-c3019.md)|increment in OpenMP 'for' statement has improper form|  
|[Compiler Error C3020](compiler-error-c3020.md)|'*variable*': index variable of OpenMP 'for' loop cannot be modified in loop body|  
|[Compiler Error C3021](compiler-error-c3021.md)|'*argument*': argument is empty on OpenMP '*directive*' directive|  
|[Compiler Error C3022](compiler-error-c3022.md)|'*directive*': invalid schedule kind of '*directive*' on OpenMP '*directive*' directive|  
|[Compiler Error C3023](compiler-error-c3023.md)|'*argument*': unexpected token encountered in argument to OpenMP '*directive*' clause|  
|[Compiler Error C3024](compiler-error-c3024.md)|'schedule(runtime)': chunk_size expression is not allowed|  
|[Compiler Error C3025](compiler-error-c3025.md)|'*clause*': integral expression expected|  
|[Compiler Error C3026](compiler-error-c3026.md)|'*clause*': constant expression must be positive|  
|[Compiler Error C3027](compiler-error-c3027.md)|'*clause*': arithmetic or pointer expression expected|  
|[Compiler Error C3028](compiler-error-c3028.md)|'*member*': only a variable or static data member can be used in a data-sharing clause|  
|[Compiler Error C3029](compiler-error-c3029.md)|'*symbol*': can only appear once in data-sharing clauses in an OpenMP directive|  
|[Compiler Error C3030](compiler-error-c3030.md)|'*identifier*': variable in '*directive*' clause/directive cannot have reference type|  
|[Compiler Error C3031](compiler-error-c3031.md)|'*identifier*': variable in 'reduction' clause must have scalar arithmetic type|  
|[Compiler Error C3032](compiler-error-c3032.md)|'*identifier*': variable in '*clause*' clause cannot have incomplete type '*type*'|  
|[Compiler Error C3033](compiler-error-c3033.md)|'*identifier*': variable in '*clause*' clause cannot have const-qualified type|  
|[Compiler Error C3034](compiler-error-c3034.md)|OpenMP '*directive*' directive cannot be directly nested within '*directive*' directive|  
|[Compiler Error C3035](compiler-error-c3035.md)|OpenMP 'ordered' directive must bind directly to a 'for' or 'parallel for' directive with the 'ordered' clause|  
|[Compiler Error C3036](compiler-error-c3036.md)|'*clause*': invalid operator token in OpenMP 'reduction' clause|  
|[Compiler Error C3037](compiler-error-c3037.md)|'*identifier*': variable in '*clause*' clause must be shared in enclosing context|  
|[Compiler Error C3038](compiler-error-c3038.md)|'*identifier*': variable in 'private' clause cannot be a reduction variable in enclosing context|  
|[Compiler Error C3039](compiler-error-c3039.md)|'*identifier*': index variable in OpenMP 'for' statement cannot be a reduction variable|  
|[Compiler Error C3040](compiler-error-c3040.md)|'*identifier*': type of variable in 'reduction' clause is incompatible with reduction operator '*operator*'|  
|[Compiler Error C3041](compiler-error-c3041.md)|'*identifier*': variable in 'copyprivate' clause must be private in enclosing context|  
|[Compiler Error C3042](compiler-error-c3042.md)|'copyprivate' and 'nowait' clauses cannot appear together on OpenMP '*directive*' directive|  
|[Compiler Error C3043](compiler-error-c3043.md)|OpenMP 'critical' directive cannot be nested in 'critical' directive with same name|  
|[Compiler Error C3044](compiler-error-c3044.md)|'section': only allowed directly nested under an OpenMP 'sections' directive|  
|[Compiler Error C3045](compiler-error-c3045.md)|Expected a compound statement following OpenMP 'sections' directive. Missing '{'|  
|[Compiler Error C3046](compiler-error-c3046.md)|Missing structured block in an OpenMP '#pragma omp sections' region|  
|[Compiler Error C3047](compiler-error-c3047.md)|Structured block in an OpenMP 'sections' region must be preceded by '#pragma omp section'|  
|[Compiler Error C3048](compiler-error-c3048.md)|Expression following '#pragma omp atomic' has improper form|  
|[Compiler Error C3049](compiler-error-c3049.md)|'*argument*': invalid argument in OpenMP 'default' clause|  
|[Compiler Error C3050](compiler-error-c3050.md)|'*class*': a ref class cannot inherit from '*identifier*'|  
|Compiler Error C3051|Obsolete.|  
|[Compiler Error C3052](compiler-error-c3052.md)|'*identifier*': variable doesn't appear in a data-sharing clause under a default(none) clause|  
|[Compiler Error C3053](compiler-error-c3053.md)|'*identifier*': 'threadprivate' is only valid for global or static data items|  
|[Compiler Error C3054](compiler-error-c3054.md)|'#pragma omp parallel' is currently not supported in a generic class or function|  
|[Compiler Error C3055](compiler-error-c3055.md)|'*identifier*': symbol cannot be referenced before it is used in 'threadprivate' directive|  
|[Compiler Error C3056](compiler-error-c3056.md)|'*identifier*': symbol is not in the same scope with 'threadprivate' directive|  
|[Compiler Error C3057](compiler-error-c3057.md)|'*identifier*': dynamic initialization of 'threadprivate' symbols is not currently supported|  
|[Compiler Error C3058](compiler-error-c3058.md)|'*identifier*': symbol not declared as 'threadprivate' before it is used in the 'copyin' clause|  
|[Compiler Error C3059](compiler-error-c3059.md)|'*identifier*': 'threadprivate' symbol cannot be used in the '*clause*' clause|  
|[Compiler Error C3060](compiler-error-c3060.md)|'*identifier*': a friend function may not be defined inside a class using a qualified name (it may only be declared)|  
|Compiler Error C3061|operator '*operator*': not allowed on enumeration '*type*' with underlying type '*type*'|  
|[Compiler Error C3062](compiler-error-c3062.md)|'*identifier*': enumerator requires value since the underlying type is '*type*'|  
|[Compiler Error C3063](compiler-error-c3063.md)|operator '*operator*': all operands must have the same enumeration type|  
|Compiler Error C3064|'*identifier*': must be a simple type or resolve to one|  
|[Compiler Error C3065](compiler-error-c3065.md)|property declaration at non-class scope is not allowed|  
|[Compiler Error C3066](compiler-error-c3066.md)|there are multiple ways that an object of this type can be called with these arguments|  
|Compiler Error C3067|an initializer list cannot be used with the built-in operator[]|  
|[Compiler Error C3068](compiler-error-c3068.md)|'*identifier*': a 'naked' function cannot contain objects that would require unwinding if a C++ exception occurred|  
|[Compiler Error C3069](compiler-error-c3069.md)|operator '*operator*': not allowed for enumeration type|  
|[Compiler Error C3070](compiler-error-c3070.md)|'*identifier*': property does not have a 'set' method|  
|[Compiler Error C3071](compiler-error-c3071.md)|operator '*operator*' can only be applied to an instance of a ref class or a value-type|  
|[Compiler Error C3072](compiler-error-c3072.md)|operator '*operator*' cannot be applied to an instance of a ref class use the unary '%' operator to convert an instance of a ref class to a handle type|  
|[Compiler Error C3073](compiler-error-c3073.md)|'*identifier*': ref class does not have a user-defined copy constructor|  
|Compiler Error C3074|an array cannot be initialized with a parenthesized initializer|  
|[Compiler Error C3075](compiler-error-c3075.md)|'*identifier*': you cannot embed an instance of a reference type, '*type*', in a value-type|  
|[Compiler Error C3076](compiler-error-c3076.md)|'*identifier*': you cannot embed an instance of a reference type, '*type*', in a native type|  
|[Compiler Error C3077](compiler-error-c3077.md)|'*identifier*': a finalizer can only be a member of a reference type|  
|Compiler Error C3078|array size must be specified in new expressions|  
|Compiler Error C3079|an initializer list cannot be used as the right operand of this assignment operator|  
|[Compiler Error C3080](compiler-error-c3080.md)|'*finalizer*': a finalizer cannot have a storage-class-specifier|  
|Compiler Error C3081|Obsolete.|  
|Compiler Error C3082|Obsolete.|  
|[Compiler Error C3083](compiler-error-c3083.md)|'*identifier*': the symbol to the left of a '::' must be a type|  
|[Compiler Error C3084](compiler-error-c3084.md)|'*identifier*': a destructor/finalizer cannot be '*keyword*'|  
|[Compiler Error C3085](compiler-error-c3085.md)|'*identifier*': a constructor cannot be '*keyword*'|  
|Compiler Error C3086|cannot find 'std::initializer_list': you need to #include <initializer_list>|  
|[Compiler Error C3087](compiler-error-c3087.md)|'*identifier*': call of '*declaration*' already initializes this member|  
|Compiler Error C3088|'*class*': attribute constructor must have named formal arguments|  
|Compiler Error C3089|'*identifier*': parameter name does not match any data member's name|  
|Compiler Error C3090|'*class*': attribute class cannot be a template|  
|Compiler Error C3091|'*class*': attribute class cannot have base classes|  
|Compiler Error C3092|'*class*': attribute class member cannot be a bit field, 'static' or 'const'|  
|Compiler Error C3093|'*type*': type not allowed for attribute class member '*member*'|  
|[Compiler Error C3094](compiler-error-c3094.md)|'*attribute*': anonymous usage not allowed|  
|[Compiler Error C3095](compiler-error-c3095.md)|'*attribute*': attribute cannot be repeated|  
|[Compiler Error C3096](compiler-error-c3096.md)|'*attribute*': attribute is allowed on data members of attribute classes only|  
|[Compiler Error C3097](compiler-error-c3097.md)|'*attribute*': attribute must be scoped with 'assembly:' or 'module:'|  
|Compiler Error C3098|'*identifier*': attribute has no user-defined constructors|  
|[Compiler Error C3099](compiler-error-c3099.md)|'*keyword*': use [System::AttributeUsageAttribute]/[Windows::Foundation::Metadata::AttributeUsageAttribute] for managed/WinRT attributes|  
