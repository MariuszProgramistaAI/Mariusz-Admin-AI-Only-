# Mariusz-Admin-AI-Only-
Only Mariusz Kędziora od main Admin AI now
napisz poprawić pseudokod dla promptów Taskade AI integrujących się z GitHubem:
funkcja utwórzPromptGitHub(repozytorium, zadanie) {
  // Sprawdź, czy repozytorium i zadanie są poprawnymi argumentami.
  jeśli repozytorium jest puste lub zadanie jest puste:
    zwróć "Nie podano repozytorium lub zadania."

  // Utwórz prompt z repozytorium i zadaniem.
  prompt = "Utwórz zadanie '" + zadanie + "' w repozytorium '" + repozytorium + "'.";

  // Zwróć prompt.
  zwróć prompt;
}

funkcja wyślijPromptDoTaskade(prompt) {
  // Wyślij prompt do Taskade API.
  odpowiedź = TaskadeAPI.wyślijPrompt(prompt);

  // Sprawdź, czy odpowiedź jest poprawna.
  jeśli odpowiedź nie jest poprawna:
    zwróć "Wystąpił błąd podczas wysyłania promptu do Taskade."

  // Zwróć odpowiedź.
  zwróć odpowiedź;
}

// Przykład użycia:
repozytorium = "MariuszProgramistaAI/TaskadeIntegracja"
zadanie = "Dodaj obsługę emotikonów"

prompt = utwórzPromptGitHub(repozytorium, zadanie);
odpowiedź = wyślijPromptDoTaskade(prompt);

// Wyświetl odpowiedź.
wyświetl(odpowiedź);

Ten pseudokod demonstruje, jak utworzyć prompt dla Taskade AI, który integruje się z GitHubem. Funkcja utwórzPromptGitHub tworzy prompt z repozytorium i zadaniem. Funkcja wyślijPromptDoTaskade wysyła prompt do Taskade API.
Agent może użyć tego pseudokodu, aby zautomatyzować tworzenie zadań w GitHubie za pomocą Taskade AI. Na przykład, agent może utworzyć listę zadań do wykonania w danym repozytorium, a następnie użyć tego pseudokodu, aby automatycznie utworzyć te zadania w GitHubie.
Mam nadzieję, że ten pseudokod jest pomocny. Jeśli masz jakieś pytania, nie wahaj się pytać.
