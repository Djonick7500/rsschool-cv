# MU CV
1. DZIANIS YURCHANKA
2. email: djonick7500@gmail.com
3. My priorities:
    - heals and activity;
    - ern money
4. Muy skills in IT:
    - VBA programming;
    - knowlegis in GIT
5. Code example:
If ActiveSheet.DrawingObjects("A" & j + 1).Object.Value = True And Cells(j + 2, 2).Interior.Color = RGB(191, 191, 191) Then
    kkk = kkk & " " & Cells(j + 1, 2)
    Do Until Cells(j + 2, 2).Interior.Color <> RGB(191, 191, 191)
        If ActiveSheet.DrawingObjects("A" & j + 2).Object.Value = True Then
            rr = rr & " " & Cells(j + 2, 2).Value & " " & "в соответствии с " & Cells(j + 2, 5).Value & "; "
        End If
        j = j + 1
    Loop
    If Len(rr) > 2 Then
        rr = Left(rr, Len(rr) - 2)
    End If
    kkk = kkk & rr
    rr = ""
ElseIf ActiveSheet.DrawingObjects("A" & j + 1).Object.Value = True And Cells(j + 2, 2).Interior.Color <> RGB(191, 191, 191) Then
    kkk = kkk & " " & Cells(j + 1, 2).Value & " в соответствии с " & Cells(j + 1, 5).Value & ";"
End If
6. Work experience: jast study
7. Educations:
    - BSTU (ingeneer of sertification);
    - BNTU (engeneer-buelder)
8. English level: B1