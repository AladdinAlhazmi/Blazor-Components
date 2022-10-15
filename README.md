# Blazor-Components


//call ModalDialog 
    <ModalDialog Title='AreYouSure'
             Text='ConfirmDelete"'
             OnClose="@OnDialogClose"
             DialogType="ModalDialogType.DeleteCancel">
    </ModalDialog>
        
        
//call ToastDialog 
   <ToastDialog IsSuccessed='true'
          ToastMessage='toastMessage'>
   </ToastDialog>
