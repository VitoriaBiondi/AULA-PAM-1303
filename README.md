<?xml version="1.0" encoding="utf-8"?>
<androidx.constraintlayout.widget.ConstraintLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:id="@+id/main"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:padding="20dp"
    tools:context=".MainActivity">

    <TextView android:id="@+id/nome"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Nome"
        app:layout_constraintTop_toTopOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        android:textSize="18sp"
        android:textColor="#2185D9"
        android:textStyle="bold"/>

    <EditText android:id="@+id/edtnome"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="ex:Vitória Biondi"
        android:layout_marginTop="10dp"
        app:layout_constraintTop_toBottomOf="@id/nome"
        app:layout_constraintStart_toStartOf="parent"/>

    <TextView android:id="@+id/cpf"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="CPF"
        android:textSize="18sp"
        android:textColor="#2185D9"
        android:textStyle="bold"
        app:layout_constraintTop_toBottomOf="@id/edtnome"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="10dp" />

    <EditText android:id="@+id/edtcpf"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="ex:000.000.000-00"
        android:layout_marginTop="10dp"
        app:layout_constraintTop_toBottomOf="@id/cpf"
        app:layout_constraintStart_toStartOf="parent"/>

    <TextView android:id="@+id/nascimento"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Data de Nascimento"
        android:textSize="18sp"
        android:textColor="#2185D9"
        android:textStyle="bold"
        app:layout_constraintTop_toBottomOf="@id/edtcpf"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="10dp" />

    <EditText android:id="@+id/edtnascimento"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="00/00/0000"
        android:layout_marginTop="10dp"
        app:layout_constraintTop_toBottomOf="@id/nascimento"
        app:layout_constraintStart_toStartOf="parent"/>

    <TextView android:id="@+id/mae"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Nome da Mãe"
        android:textSize="18sp"
        android:textColor="#2185D9"
        android:textStyle="bold"
        app:layout_constraintTop_toBottomOf="@id/edtnascimento"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="10dp" />

    <EditText android:id="@+id/edtmae"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:hint="ex: Maria Luiza"
        android:layout_marginTop="10dp"
        app:layout_constraintTop_toBottomOf="@id/mae"
        app:layout_constraintStart_toStartOf="parent"/>

    <Button android:id="@+id/entrar"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Voltar"
        android:textColor="#FF5722"
        app:cornerRadius="0dp"
        app:layout_constraintTop_toTopOf="@id/edtmae"
        app:layout_constraintEnd_toStartOf="parent"
        android:layout_marginTop="80dp"
        android:backgroundTint="#E4FFFFFF"/>

    <Button android:id="@+id/voltar"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Entrar"
        app:cornerRadius="0dp"
        android:textColor="@color/white"
        app:layout_constraintTop_toTopOf="@id/entrar"
        app:layout_constraintStart_toStartOf="parent"
        android:layout_marginTop="80dp"
        android:padding="15dp"
        android:backgroundTint="#FF5722"/>






</androidx.constraintlayout.widget.ConstraintLayout>
