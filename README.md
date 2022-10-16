# Blazor-Components


//call ModalDialog
```cs
<ModalDialog Title='AreYouSure'
         Text='ConfirmDelete"'
         OnClose="@OnDialogClose"
         DialogType="ModalDialogType.DeleteCancel">
</ModalDialog>
```     
        
//call ToastDialog 
```cs
<ToastDialog IsSuccessed='true'
      ToastMessage='toastMessage'>
</ToastDialog>
```
